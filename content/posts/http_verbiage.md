---
title:  "HTTP verbiage and its abuse"
date:   2019-04-02 14:20:00 -0400
categories: http verbiage get post
epistemic: believed
importance: 6
---

I've noticed a trend in my experience working on bigger server-side projects
that, apart from being just plain annoying, is actually somewhat harmful -
**the chronic and repeated misuse of HTTP verbiage.** I'm not exactly sure why,
when server-side development is being taught, we're not imprinting the importance
of these semantics on students, at least as a whole. Time and time again I've
seen GET requests misused to submit information and change state, POST requests
used to retrieve information transparently, and in general a reluctance to 
change this habit. So what's the problem with each practice?


GET as a statement with side effects
------

This is one of my biggest pet peeves as a whole, for one very, very crucial
reason:

**GET requests can and will be stored by browsers in order to retrieve content on the fly, especially for things like favourites.**

This means that relying upon a GET request to change state is not only a annoying
semantic mistake, it's also potentially fraught with side effects. A somewhat
[famous tweet](https://twitter.com/rombulow/status/990684453734203392) outlines
a potential worst-case scenario come to life. GET requests should be free of 
side effects, because the standard _expects_ them to be, and therefore you do
_not_ have control over what a browser vendor will do with that URL.

POST to retrieve data / stateless changes
------

The exact opposite effect is in play here: POST requests are made for POSTing
information to a server - not to present said information. Retrieving information
via a POST request means that you're going to break user-interfacing functionality,
like caching, bookmarking, etc. This is less common, but I've seen it done before,
especially when it comes to database queries. **Database queries for retrieving information should be considered stateless, and can fall under the banner of GET requests.**


TL;DR
------

Don't use POST for retrieval, and don't use GET for posting information or
records to a server. Both of these have implications beyond pure semantics,
and can cause unintended consequences further down the line.