+++
title = "The Buterin Questions, #4 How can Decentralized Apps Work Well Even with 5-10 Second Block Latency?"
date = "2018-08-15T13:47:08+02:00"
author = "David Ritter, Arnaud Bauer and Steve Melnikoff"
tags = ["tech, Buterin, large scale"]
categories = ["Technology Development"]
+++

Introduction: WeChat has some excellent channels for lively and informative discussions focussing on blockchain technologies. Ethereum co-founder Vitalik Buterin recently posted a set of blockchain ‘hard questions’ to one of these, and we are publishing responses here in Medium from Penta Global as a way to extend the conversation across the wider blockchain community, with hopes of furthering the conversation and a productive exchange of ideas. <!--more-->

<img src=/img/blog/scale-up-with-the-cloud.jpg alt="img one">

Q: How can decentralized apps work well even with 5-10 second block latency?

A: Open to interpretation here, what is meant by a decentralised app working ‘well’? Now this Buterin question is posed in the context of 5-10 second block latencies. Maybe one answer lies in an understanding of DApp performance and blockchain scaling issues. 

Scale or ‘scaling’ can be defined as: “a system capable of handling the transactional demands of any competing system providing the same service(s) to the same arbitrary set of users across the globe. Examples of ‘services’ include: streaming video, message notifications, or maintaining balances on a ledger.”

Under this definition meeting scaling requirements means building robust and high-performance DApp platforms. For which ‘Sharding’ is an area of innovation that Ethereum, Penta, and other blockchain projects are working on. Sharding offers one promising solution, because it can increase throughput without forfeiting decentralization. 

Ideas behind Sharding have their legacy extending into both the database and distributed computing communities. There the problems of large database tables or compute problems are ‘broken down’ (‘sharding’) into smaller chunks, or subproblems, called ‘shards’. Each of which can then be handled by individual nodes, for performance increases ‘scaling’ with the number of nodes available.

Blockchains can do the same. Instead of every node processing each and every transaction, and storing the global (entire) state of the blockchain ledger, ‘islands of nodes’ can simply process a portion of the overall transaction stream, for dramatically increased network efficiencies.

Unlike its centralised database and distributed (computing) cousins, blockchain’s version of Sharding brings with it the challenge of ‘imperium in imperio’ or ‘an empire within an empire’. That is, in order to retain the main benefits of decentralization, ledger data that is complete, accurate and consistent with every other copy held by all the nodes of the network; shards must be eventually aggregated back into a global ledger that is also: complete, accurate and consistent. 

Though progress is being made towards a comprehensive implementation of Sharding, robustly addressing the shard assembly problem, it is still a promised future awaiting full realization.

Back to the original question. While many blockchain platforms look to the promise of Sharding, our development team at Penta Global takes a broader view of DApps working well. It is as part of our mission to be the ‘universal blockchain connector’. That view ties in with the recognition that a majority of DApps will not be digital wallets focussed solely on cryptocurrency. 

Penta truly believes DApps are the tools and (mobile technology) helpers for the smart digital economy. An economy that is transitioning from operating entirely in a trusted, centralised environment, to a highly efficient ecosystem that will function to a good extent utilising blockchain in decentralized, peer-to-peer fashion.

A key to really answering Buterin’s question is understanding and accepting that most DApps will utilise both centralised data services as well as blockchain. Yes, we still need to look at evolving blockchain technology overall.  But most important, we need to provide the right tools to the developer community, in the form of apis to build robust solutions which successfully combine a decentralized ledger (database) and centralized services (computing/REST layer) for vigorous DApps that work well even with 5-10 second block latencies.

References

1. ‘The DCS Theorem’, Greg Slepak, Anya Petrovya, https://arxiv.org/abs/1801.04335, January 2018.

2. ‘What is Sharding? Guide to this Ethereum Scaling Concept Explained’, Brian Curran, https://blockonomi.com/sharding/, July 2018.

3. ‘Vitalik Buterin: “Scaling is Ethereum´s Priority and Casper Is on the Way” ’, Ricardo Carrasco, https://www.bitrates.com/news/p/vitalik-buterin-scaling-is-ethereum-s-priority-and-casper-is-on-the-way-, March 2018.

4. ‘Quantifying Decentralization’, Balaji S. Srinivasan, https://news.earn.com/quantifying-decentralization-e39db233c28e, July 2017.

5. ‘Decentralization in Bitcoin and Ethereum Networks’, Adem Efe Gancer et.al., https://arxiv.org/abs/1801.03998, March 2018.
