---
layout: page
title: Blockchain-based Process Engine
description: blockchain, bpm, privacy-aware
#img: /assets/img/12.jpg
---


More and more business requirements are crossing organizational boundaries, which makes cross-organization business process management increasing desirable in today’s business world. However, the lack of mutual trust among different organizations is often a roadblock. Blockchain platforms allow a set of actors to maintain a ledger of transactions without relying on a central authority, and this feature can be used as a basis for executing cross-organization collaborative business processes among mutually untrusting parties. One of the latest work [1] has introduced such a blockchain-based engine with the source code available at [2]. However, the proposed system has one major issue: it complies the whole cross-organization business model into a set of smart contracts. This would be not efficient in terms of system executions. Moreover, the business privacy of each organization is not protected properly [3]. In this project, our target is to develop a privacy-aware cross-organization business process execution engine on the Ethereum blockchain by improving and extending the existing implementation [2] with new features.


[1] Caterpillar: A business process execution engine on the Ethereum blockchain. Softw: Pract Exper, 2019.
[2] https://github.com/orlenyslp/Caterpillar
[3] Towards Comprehensive Support for Privacy Preservation Cross- organization Business Process Mining. IEEE Transactions on Services Computing, pp. 1-15, 2016.
