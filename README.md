# PeerReview
An attempt at describing issues with traditional peer review and proposing a platform/system design to address them.

This is simply a proposal. I have been thinking about this problem for a few months, and started to put some concepts together at/for ETHDenver. I came as a solo hacker with an idea and some background in the space, but without much technical expertise.

If this project seems at all interesting or important to you, and you have some time or expertise you can lend, PRs are encouraged ;)

Problems: 
Peer review and in traditional journal format takes months to a year to go through the review process including revisions and     publication. Particularly in fast moving spaces like the blockchain space, this is not functional.
Peer reviewed research is often paywalled, leaving the average person out of access without a payment or relationship with a major academic institution that pays for access.
Researchers and reviewers are expected to contribute to this system without receiving any payment.
Transitioning an extremely traditional process with serious implications to our notions of truth and fact is likely to be met with resistance, and with blockchain tech having friction of its own, onboarding new users needs to be as frictionless as possible.

Proposal: 
By adding incentive layers to the process, we can recognize that contributions to the space is labour. This could have an effect on the speed at which reviews could be done, though this is a theoretical effect based on the incentive layer affecting prioritization and reduction in time required to meet financial needs.
Verifying large numbers of individuals with valid credentials to whitelist could also increase the speed of reviews and the strength of reviews in numbers. There could also be a curation/weighted vote added to reviews by qualified members. This could be done using an oracle built off of university graduation lists as they exist, but could be built out to higher validation criteria.
Onboarding a group that likely does not have crypto could be done using a similar props system described by Austin Griffith in his etherjamjam project. By utilizing meta-transations and relayers, we can onboard users and give them a small amount of skin in the game while holding education on things like metamask until they understand the concepts.
Rather than using their own ETH to give props for good reviews, users instead give an upvote of sorts that then translates into an eth reward from a pool. Somewhat similar to steemit and reddit.
Funding for the incentive layers could come from a number of potential sources. A Curved Bonded Token could be issued or be built into a bonded token ecosystem, a pool of funds (donated, seeded, etc?) could payout a percentage of the funds based on activity, or potentially have a grant proposal through something like Moloch or similar. Could be crowdfunded, sponsored, or some combination.
Proposals could also be evaluated and/or curated using a quadratic voting formula.
Publishers could stake tokens to payout to reviewers.
Documents would be hosted on IPFS.

Future:
This could also work as a curated news aggregation or as a fact checking/sourcing on media.
Both gets non-users into the ecosystem in a more streamlined way and allows them to contribute, while treating data as labor and remunerating reviews.


Potential Issues:
There should be a layer between the reward and the upvoter to reduce abuse and "buying influence" in the system.
There could be some sort of delay, as well as/or a maximum number of upvotes per user per time period. Maybe based on their continued utility (a gamified leveling system maybe? Potential to be voted down or to lose levels from inactivity too)



Notes:
Peer review system that uses Austin Griffiths work for onboarding and giving props. Could enable well supported feedback to both rise to the top and be remunerated in ETH. 

Both gets non-users into the ecosystem in a more streamlined way and allows them to contribute, while treating data as labor and remunerating reviews. Funds could come from a pool, or maybe integrated into a bonded token ecosystem.

Users would have to be added to a whitelist somehow, and rather than using their own ETH to give props for good reviews, they instead give an upvote of sorts that then translates into an eth reward from a pool. The pool could be donated, seeded, or whatever, but there should be a layer between the reward and the upvoter to reduce abuse and "buying influence" in the system.

There could be some sort of delay, as well as/or a maximum number of upvotes per user per time period. Maybe based on their continued utility (a gamified leveling system maybe? Potential to be voted down or to lose levels from inactivity too)

Publishers could stake tokens to payout to reviewers as well

the demo video of Austin Griffiths system for onboarding and giving props

https://youtu.be/cNcSXovVPdg

This is a blog post that goes into incentivized funding pools (https://tokeneconomy.co/on-bonding-curves-and-charitable-giving-9bf74b9343d2) which could be a proposed funding option but probably not one that would be built here. One example that might be similar is moloch that just went to the mainnet today.
https://twitter.com/ameensol/status/1095958134458179584?s=19

IPFS doc hosting?

Example graduate lists that could potentially be used as data for verifying credentials:
https://www.bsu.edu/news/dean-and-graduate-lists/graduate-list?search=true&term=201810&lastName=&state=0&city=&county=0&degree=BA 
https://www.nmu.edu/mc/GraduatesList 
