---
title:  "Energy and Decentralization"
date:   2019-06-26 10:25:00 -0400
updated: 2019-10-06 17:53:00 -0400
categories: climate energy decentralization
epistemic: semi-believed
importance: 7
---
It's no small secret that climate
change is here, and is absolutely something to worry about. It's also no small
secret that this is, in no meager part, the fault and responsibility of humankind
post-industrialization. Our consumption of fossil fuels continues to demand more
and more from the environment, and our increasing dependency on the services these
fuels power makes the demand on alternative energies all the more strenuous and
exhausting.

We continue to ask questions about when our leaders, policy-makers, and tycoons
will make a concentrated switch to renewable or carbon-neutral energy sources,
and because of money, logistics, greed, and lobbying, the answer rarely is honest 
or agreeable.

Part of the onus, then, falls back to us, as consumers. How can we, on an individual
and semi-collective scale, influence our environment and lower our consumption?

As a programmer and technologist, I cannot accurately comment on household habits that might
help to lower your personal consumption of fossil fuels, nor can I suggest community initiatives
that might bring acute local awareness to the plight of fossil fuel consumption. However,
I do exist in a sphere that, as of right now, remains a moderately large consumer of
energy globally. Gelenbe and Caseau (2015) put the pre-2013 number at around 4.7% of global
consumption, although this has inevitably ballooned thanks to the rise of mainstream cryptocurrency
in the interim between 2012 and 2019[^2]. Indeed, a projection by Andrae and Edler (2015) of a worst-case
number for global technological energy consumption by 2030 clocks at about 51% 
of global energy consumption, and approximately 23% of global greenhouse gas emissions.

These numbers, although alarming, are the worst of the worst case - the actual projected trend
is immensely modest comparatively. However, even the best case projections highlight
a fairly clear-cut conclusion - consumer devices are not the main consumers in the
ICT pool:

{{< figure src="/img/consumer_elec_graph.png" title="A graph of consumer device power trends" >}}

An estimated worst-case power demand of 1,108 TWh[^3] is expected, according to 
Andrae and Edler, to be about 1.82% of global energy production during 2030
(which Andrae and Edler pins at about 61,000TWh). This can easily be compared
to something like, for example, consumer device _production_, which at worst-case 
outclasses actual usage of consumer devices phenomenally:

{{< figure src="/img/production_elec_graph.png" title="A graph of consumer device production power trends" >}}

Indeed, like many forms of industrial waste, the electrical demand of producing
modern consumer devices appears heart-wrenching. Of course, a closer look at the
graph shows a large disparity between the worst and "expected" case predictions,
a difference of 10.6%[^4] of estimated global energy production at worst and 1.48% 
expected. So even this, alone, has some issues, and cannot account alone for
the ludicrous number projected by Andrae and Edler earlier.

So what possible cause is there?

Data centers are an unfortunate reality in modern computing, and unless you've 
worked in, seen, or researched them, it's unlikely you've considered the energy
waste they represent. Large, powerful servers are put to work, nearly 24/7,
servicing requests at any given moment. This already represents a power cost - 
unlike consumer devices with consumer workloads, these are beefy machines with
an unbridled slew of connections. Constant work, a decked-out spec list, and the
icing on the cake - there's more than one of them! Indeed, larger data centers (like those
that amazon distributes across the globe) can contain around [50,000 to 80,000](https://www.forbes.com/sites/johnsonpierr/2017/06/15/with-the-public-clouds-of-amazon-microsoft-and-google-big-data-is-the-proverbial-big-deal/#3d31b0e02ac3) servers. This, in addition to the fact that all of these servers
are required to be kept _cool_ constantly (A/C is expensive, as any homeowner 
will tell you), makes it immediately clear that these data centers will and do
consume lots of energy.

It's no surprise then that even the most bullish estimate for data center 
consumption in the year 2030 is _29 terawatt-hours_ above the 
_worst_-case estimate of consumer device consumption:

{{< figure src="/img/data_elec_graph.png" title="A graph of data center power trends" >}}

The disparity between the worst and expected case is still fairly high, but it's
not such good news this time: at worst, we'd be seeing a percentage of global production
around 13%[^5], while the more realistic number is estimated at around 4.86%.

There are plenty of major changes we could make at any point at an individual level
to correct things like the overproduction of consumer devices - for one, keeping
our devices longer, and attempting to adapt our personal workflows into more
low-spec conscious routines, such as less powerful or "pretty" editors, or moving 
more taxing workloads to dedicated computers that can upgrade easily rather than 
being thrown away completely. Additionally, we can adapt in some of the same ways
to combat the positively minute effect each one of us has at a consumer device level.

## Data Centers and Renewable Energy

One point for consideration in this discussion is the heavy reliance and
subsequent zoning of these data centers near sources of renewable energy.
Testaments from major players in the industry of setting up data centers tend to
pride themselves on the use of renewables in the day-to-day operations of their
buildings. 

Google touts that they are the 
[largest corporate purchaser of renewable energy](https://www.blog.google/outreach-initiatives/environment/meeting-our-match-buying-100-percent-renewable-energy/) 
in the world. Additionally, Google advertised an efficiency of nearly
[50% over the industry standard](https://sustainability.google/projects/machine-learning/)
in the spring 2014, with further apparent reductions being made through
the application of [machine learning](/pdf/gao_2014.pdf) in optimizing the 
facility. These steps of taking pre-existing (and always expanding) infrastructure
and continuing to refine the formula in multiple avenues is admirable[^6].

Amazon's data on data center sustainability is buried a bit deeper, being
seemingly separated from their main sustainability initiatives (which are,
unsurprisingly, focused on their "primary" business of selling goods), and
instead located on their
[AWS homepage](https://aws.amazon.com/about-aws/sustainability/). Amazon owns
an array of wind and solar farms, and, as of April of 2019, has committed to four
new installations in Europe and the United States. AWS is apparently
[at least 50% renewable](https://aws.amazon.com/about-aws/sustainability/sustainability-timeline/)
as of 2018, but the data (like Google) is somewhat nebulous and in vague percentages.
Additionally, Amazon [buys and retires "environmental credits"](https://aws.amazon.com/about-aws/sustainability/#AWS_purchases_and_retires_environmental_attributes,_like_Renewable_Energy_Credits_and_Guarantees_of_Origin,_to_cover_the_non-renewable_energy_we_use_in_these_regions.)
in subsequent proportion to their non-renewable usage.

Google's position on this, in my opinion, reaches the key 
threshold between idealistic and practical. Purchasing renewable energy to match 
your consumption is an admirable goal, especially when it leads to more
renewable energy being available in local power grids. Amazon takes part in
this too, but has spent more money and time investing in bootstrapping its
energy in order to conquer the "renewable energy used" figure. This is fine, and
theoretically more of a "green" initiative than simply matching your consumption,
but it seems to be more self-serving than anything. It eschews practicality for
idealism, which is why I look at it as more of a flight of fancy. Nevertheless,
50% is not insignificant for a powerhouse like AWS, nor will I disagree with
a company attempting to clean up its energy usage. 

-----------

## References:

[The Impact of Information Technology on Energy Consumption and Carbon Emissions](/pdf/a1-gelenbe.pdf) by Erol Gelenbe and Yves Caseau

[On Global Electricity Usage of Communication Technology: Trends to 2030](/pdf/andrae_edler_2015.pdf) by Anders S. G. Andrae and Tomas Edler

[^2]: Please note: this will not be a discussion about cryptocurrency, although I'd like to tackle this as a sort of "part 2" to this article.

[^3]: Graph and statistic both sourced from Andrae and Edler (2015).

[^4]: Ibid.

[^5]: Ibid.

[^6]: It's easy to take the reductionist viewpoint here, and claim that it's simply a matter of marketing or finances. Yes, a side effect of switching to renewable energy sources is looking "hip," and as a result of increased penetration in the energy market, along with various inevitably subsidies, renewable sources are sometimes cheaper. It stands to reason, however, that pure cynicism can't completely encapsulate Google's steps as an entity. A sea change so massive in a company so large is inevitably composed of multiple people, all of whom I have a hard time believing are so cynically narrow-minded.

