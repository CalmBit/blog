---
title:  "Gopher, and why the internet is broken (and why that's probably okay)."
date:   2019-03-15 05:25:00 -0400
categories: gopher html http
epistemic: believed
importance: 4
---
I think the broader internet has, for a while now, come to the unsurprising 
conclusion that the internet, as we know it, is siloed and broken. I hesitate 
to think that this is particularly controversial, but it remains clear in my
eyes that the continued centralization and "ecosystemization" of tech has
systematically and unapologetically butchered the original "meaning" behind it.
What started out, at its most basic, as a way to display rich, knowledgable
hypertext has been bent repeatedly in order to adapt to a load of various
technologies, culminating in the current technological landscape. An ongoing
joke in web design has been the absolutely _massive_ level of boilerplate
needed in order to produce a modern website, including the pre-requisite
mass of node modules required for a functioning web-scale, fully reactive, 100%
free-range JavaScript SPA.

Nevertheless, this isn't _necessarily_ indicative of a landscape that must,
under any circumstances, adapt to the whims of people like me, who would much
prefer a more decentralized technological ecosystem. The internet, for all of
its many, many flaws, remains, at its core, good for the purpose it has evolved 
to meet: 
_serving a vast array of exciting, interesting content with lots of polish._
I wouldn't for a second suggest that this needs to change - it serves an 
important purpose in our daily lives. Moreover, I think it 
would be regressive to suggest that, because I _personally_ see a proliferation 
of "bloated" website design as an issue, it must change or be "fixed." 

I won't however, deny that my interest has been whetted by the re-adoption 
of older technologies, such as Gopher (as the title names). Though lacking a 
great deal of "modern" polish, the underlying ethical and technological
framework of these older technological solutions remains indisputably 
attractive: a revival of the hacker "ethos" of creating simple solutions to
problems.

Gopher and like technologies aren't silver bullets to the problems we face with
the internet: a fundamental re-evaluation of the way we interact with our
massive data silos seems underway, barring any individual's particular
contribution to said "awakening." But, at their core, it's quite possible we 
could learn some things from the so-called "predecessors" of the web.

Simplicity
==========
Trying to view a massive, modern website in a browser like Lynx, lacking 
JavaScript, is an exercise in futility, save from some particularly 
well-behaving outliers. Meanwhile, Gopher websites, in their simplicity, 
look presentable no matter how you slice them: there's no styling to worry about
calculating, no code to execute, just a plain ol' directory with a bunch of 
files and subdirectories.

Resilience
===========
Modern websites use a lot of moving parts to keep everything going: even static
websites, like this blog, use a metric tonne of dependencies and assets in order
to keep everything pretty and easy to maintain. The more moving parts you've
got, the more likely something is to break. With Gopher, most everything[^1] is a
flat file structure, just like traditional website design.

---

It's unfair to suggest that this is a one-way street though - what can we learn
in the hindsight of our years maturing the standards underlying the web?

---

Cruft/Antiquity
=============
I'm not talking stylistic here - as a programmer, my aesthetic sense is
permanently and irrevocably warped. Instead, I'm talking about the finer
points of building a Gopher client in 2019. Gopher, in its official 
specification, supports entries for 
[CCSO Nameservers](https://en.wikipedia.org/wiki/CCSO_Nameserver) and
[IBM 3270](https://en.wikipedia.org/wiki/IBM_3270) telnet support. Neither of
these technologies are in particularly pervasive usage nowadays, and it remains
_increasingly_ unlikely that they will make a comeback[^2].

Styling
========
_Yes_, yes - I made something resembling a case for a lack of styling up
in my section on Simplicity, and as aforementioned, I can't really put in
a word for aesthetic to save my life, but for god's sake, not everyone has had 
their common sense and taste ripped out of their skulls like I have - in 2019, 
people will expect something to look halfway to decent, and want to be able to 
express themselves in the content they're serving. I'm not even talking
extreme, just...maybe colours? I don't know, I'm not very good at this.

TL;DR
=======
 The web is sorta broken, but that's okay? Let's just find ourselves
a different playground and try to make it cooler while keeping what makes it
awesome.

[^1]: This is _almost_ always the case - things like integrated search do require more complexity (i.e. another server) than just a "flat-file."

[^2]: Two main caveats here: **a.)** CCSO Nameservers are actually _kinda_ cool, and I remain slightly convinced/hopeful that if Gopher saw a wider re-adoption, we could see a simultaneous re-proliferation of these servers as a result. **b.)** Yes, there's plenty of arguments that legacy code is extremely handy for unforeseen circumstances, and that it's super cool to see older devices running modern code. _However_, despite this, for common, casual usage, no soul will (god willing) have to interact with old display terminals from the early seventies. And if they ever have to, something tells me interacting with a Gopher site will be the last thing on their mind.