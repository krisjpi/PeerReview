# PeerReview
An attempt at describing issues with traditional peer review and proposing a platform/system design to address them.

This is simply a proposal. I have been thinking about this problem for a few months, and started to put some concepts together at/for ETHDenver. I came as a solo hacker with an idea and some background in the space, but without much technical expertise.

If this project seems at all interesting or important to you, and you have some time or expertise you can lend, PRs are encouraged ;)

Problems:
- Peer review and in traditional journal format takes months to a year to go through the review process including revisions and
publication. Particularly in fast moving spaces like the blockchain space, this is not functional.
- Peer reviewed research is often paywalled, leaving the average person out of access without a payment or relationship with a 
major academic institution that pays for access.
- Researchers and reviewers are expected to contribute to this system without receiving any payment.
- Transitioning an extremely traditional process with serious implications to our notions of truth and fact is likely to be met 
with resistance, and with blockchain tech having friction of its own, onboarding new users needs to be as frictionless as possible.

Proposal: 
- By adding incentive layers to the process, we can recognize that contributions to the space is labour. This could have an effect 
on the speed at which reviews could be done, though this is a theoretical effect based on the incentive layer affecting prioritization 
and reduction in time required to meet financial needs.
- Verifying large numbers of individuals with valid credentials to whitelist could also increase the speed of reviews and the 
strength of reviews in numbers. There could also be a curation/weighted vote added to reviews by qualified members. This could be 
done using an oracle built off of university graduation lists as they exist, but could be built out to higher validation criteria.
- Onboarding a group that likely does not have crypto could be done using a similar props system described by Austin Griffith in 
his etherjamjam project. By utilizing meta-transations and relayers, we can onboard users and give them a small amount of skin in 
the game while holding education on things like metamask until they understand the concepts.
- Rather than using their own ETH to give props for good reviews, users instead give an upvote of sorts that then translates into 
an eth reward from a pool. Somewhat similar to steemit and reddit.
- Funding for the incentive layers could come from a number of potential sources. A Curved Bonded Token could be issued or be built
into a bonded token ecosystem, a pool of funds (donated, seeded, etc?) could payout a percentage of the funds based on activity, or
potentially have a grant proposal through something like Moloch or similar. Could be crowdfunded, sponsored, or some combination.
- Proposals could also be evaluated and/or curated using a quadratic voting formula.
- Publishers could stake tokens to payout to reviewers.
- Documents could be hosted on IPFS, or potentially github or a github clone? Need to design a way to host documents in a way that 
can be commented on like google docs collaboration and commenting with an integrated weighted voting mechanism.

Future:
- This could also work as a curated news aggregation or as a fact checking/sourcing on media.
- Both gets non-users into the ecosystem in a more streamlined way and allows them to contribute, while treating data as labor and 
remunerating reviews.

Potential Issues:
- There should be a layer between the reward and the upvoter to reduce abuse and "buying influence" in the system.
- There could be some sort of delay, as well as/or a maximum number of upvotes per user per time period. Maybe based on their continued utility (a gamified leveling system maybe? Potential to be voted down or to lose levels from inactivity too)
- Need a way to effectively evaluate trust/reputation in the system that can take both positive and negative hits. Staking mechanism?



Notes:

Peer review system that uses Austin Griffiths work for onboarding and giving props. Could enable well supported feedback to both rise 
to the top and be remunerated in ETH. 

Both gets non-users into the ecosystem in a more streamlined way and allows them to contribute, while treating data as labor and 
remunerating reviews. Funds could come from a pool, or maybe integrated into a bonded token ecosystem.

Users would have to be added to a whitelist somehow, and rather than using their own ETH to give props for good reviews, they instead
give an upvote of sorts that then translates into an eth reward from a pool. The pool could be donated, seeded, or whatever, but there 
should be a layer between the reward and the upvoter to reduce abuse and "buying influence" in the system.

There could be some sort of delay, as well as/or a maximum number of upvotes per user per time period. Maybe based on their continued 
utility (a gamified leveling system maybe? Potential to be voted down or to lose levels from inactivity too)

Publishers could stake tokens to payout to reviewers as well

the demo video of Austin Griffiths system for onboarding and giving props
https://youtu.be/cNcSXovVPdg

Original paper on Curved Token Bonding by Simon de la Rouvierre: 
https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5

Blog post that goes into incentivized funding pools utilizing the curved token bonding concept: 
https://tokeneconomy.co/on-bonding-curves-and-charitable-giving-9bf74b9343d2 

A particularly relevant piece that Simon just posted on verified curation markets:
https://medium.com/@simondlr/verified-curation-markets-graduating-token-bonding-curves-b3885cd1108

Another example of pool funding for grants that might be similar is moloch that just went to the mainnet recently: 
https://twitter.com/ameensol/status/1095958134458179584?s=19

IPFS doc hosting?

Example graduate lists that could potentially be used as data for verifying credentials:
https://www.bsu.edu/news/dean-and-graduate-lists/graduate-list?search=true&term=201810&lastName=&state=0&city=&county=0&degree=BA 
https://www.nmu.edu/mc/GraduatesList 

Incentivisation and Data as Labour from Radical Markets: (http://radicalmarkets.com/chapters/data-as-labor)

In our chapter 5, we show that by treating Data as Labor (DaL) not only can we build a fairer and more equal society, but we can 
also spur the development of technology and economic growth. At present, because data suppliers are not properly rewarded for their
digital contributions, they lack the incentive or freedom to contribute the high-quality data that would most empower technology or
develop their personal capacities to maximize their earnings and contributions to the digital economy. The current wasteful equilibrium
results from the dominance of companies like Facebook and Google that thrive off free user data. But other companies, like Amazon, 
Apple and especially Microsoft, have a different business model and could benefit from competing with Facebook and Google to offer 
users a fairer deal. Awareness among users of their value would already make a large difference, as users might form data labor 
unions to demand fair compensation. And users are increasingly being empowered by new definitions of property rights over data in 
the European Union.
