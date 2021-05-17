# Background

## 1. Mesh Networks

![](https://miro.medium.com/max/60/0*oE7qF7PYzy1vhDXR?q=20)

![](https://miro.medium.com/max/1400/0*oE7qF7PYzy1vhDXR)

Photo by [Sander Weeteling](https://unsplash.com/@sanderweeteling?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)



A mesh network is a type of computer network, specifically a topology ( virtual layout of devices on a computer network), in which devices (hereafter nodes) communicate with each other in a point-to-point (peer-to-peer) fashion, rather than communicating with each other via a centralized access point such as in a star topology[1].

In reference to the Open Systems Interconnections (OSI) model, a mesh network focuses on layer 1–3 (physical, data link, and network) [1].

The Physical Layer is the “physical equipment involved in the data transfer” [11]. The Data Link Layer is for transmitting data between devices on the same network [11]. The Network Layer is for transmitting data between devices on different networks [11].

> ***OSI layers***

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application [11].

In a star topology, the central access point relays data traffic across the network (sending and receiving data) on behalf of nodes. While in a mesh topology, nodes send data directly to other nodes [1].

Routing protocols describe how nodes communicate (i.e., data traffic) on the network [1]. Routing protocols are in Layer 3 of the OSI model [1]. Routing protocols also employ routing tables to keep track of nodes and routes [1]. Routing protocols, in particular for mesh networks, there are three types of routing protocols: “ proactive, reactive, or hybrid” [1].

In a proactive routing protocol, the nodes are in a state of constant discovery of routes (nodes are constantly informing each other of route changes) [1]. Proactive routing protocols have self-healing properties because the network can recover even if nodes leave the network or routes are interrupted [1]. In a reactive routing protocol, “routes [are established] on demand” [1]. “For each connection they have to inquire the whole network to search for the correct path” [1]. In a hybrid routing protocol, aspects of proactive and reactive routing protocols are combined [1].

There are two connection arrangements in mesh networks: full connection and partial connection [1].

In a full connection, “each node is directly connected to all other nodes in the network. In contrast, a partial network is when only some nodes are connected to all the others, and others are only connected with the nodes with which they exchange the most data” [1].

> ***Benefits***

The major benefits of mesh networks can be summarized as:

* removal of central points of failure
* networks are “robust, self healing, and resilient”
* “ The network works with minimal infrastructure and can therefore be deployed faster at a lower cost than traditional infrastructure.”
* nodes on the network can re-route traffic thus allowing for many devices to be connected in a wide area
* removal of central authority over the network (thus, the possibility of creating a local community wireless network)
* stronger resilience and faster speeds are more nodes join the network
* securing privacy over your web requests [1][3][4].

With benefits of course come drawbacks and difficulties, such as:

* market and regulatory pressure on deploying mesh networks
* lack of incentive for telecom providers to develop because they replace middlemen
* tough to troubleshoot and manage
* cost of deployment can be problematic [1].

## 2. Community Wireless Networks

![](https://miro.medium.com/max/60/0*WkwJg4FNS6YiKkJj?q=20)

![](https://miro.medium.com/max/1400/0*WkwJg4FNS6YiKkJj)

Photo by [“My Life Through A Lens”](https://unsplash.com/@bamagal?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)

The potential of mesh networks has led to the rise of community wireless networks [2] [3]. In community wireless networks, mesh networks will be deployed so that communities can develop and own their own network infrastructure that then connects to a traditional internet service provider (ISP) via an internet gateway [3][9][10].

A major push for the growth of mesh networks are incentivized mesh networks, in which node son the network are incentivized to join, maintain, and grow the network’s infrastructure through an incentive (e.g., being paid in cryptocurrency to traffic data) [4].

The major benefits of community wireless networks are summarized as follows:

* Cheaper pricing for monthly internet access and new pricing plans such as pay-as-you-use [3][9][10][16]
* secure communications by encrypting data sent between nodes, and the network act as a virtual private network (VPN) by having an exit node (a node connected to an internet gateway) handle web requests [3][9]
* stronger resilience and faster speeds as more nodes join the network[3][4]
* an ownership and governance stake in the affairs of the network [3][4][9][10]
* lower barriers of entry to join and participate in a wireless network [5]

## 3. Blockchain, Payments, and DAOs

![](https://miro.medium.com/max/60/0*S8ymrYt_5kubFDKq?q=20)

![](https://miro.medium.com/max/1400/0*S8ymrYt_5kubFDKq)

Photo by [Launchpresso](https://unsplash.com/@launchpresso?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)>

***Blockchain-based Payment Systems***

A particular use case for blockchain is for payments systems [12]. The most popular payment system being Bitcoin (and cryptocurrency of the same name) [12]. What makes blockchain especially good for payment systems relates to blockchain’s ability to minimize trust such that a decentralized, peer-to-peer network can replace a centralized third party’s role in preventing *double-spending (spending the same money twice) *and fraud* *in electronic payment transactions[12].

> ***Blockchain & Smart Contracts***

Blockchain is an append-only, digital public ledger which allows a peer-to-peer network of computers to verify the authenticity of data without the need for a central authority [12].

Smart-contracts (do not confuse with legal contracts) are self-executing programs, stored on a blockchain, that facilitate the exchange of value (can be anything) between parties based on agreed-upon terms [13].

> ***Decentralized Autonomous Organization***

A Decentralized Autonomous Organization (DAO) is a blockchain-based organization (i.e., an organization programmed by smart contracts that are stored on a blockchain) wherein members interact with each other around a “self-enforcing open-source protocol,” often tied to the DAO’s native cryptocurrency or token[15]. The major benefits of a DAO is increasing transparency over an organization’s rules (e.g., bylaws), membership and actions to stakeholders, stronger security through blockchain and smart contracts for on-chain digital asset management, all the while having a high level of formalization (i.e., rules and requiring them to be followed) through the open source protocol [15]. Members are incentivized to contribute to the growth of the DAO by receiving cryptocurrency or tokens for completing tasks on the DAO’s behalf [15]. Thus, DAOs allow for blockchain’s benefit of trust minimization for organizations such that DAO members can rely on lower levels of trust than in a traditional organization before working together [15]. DAOs generally operate in a non-hierarchical, horizontal governance manner, similar to cooperatives (you could say DAOs are quasi-cooperatives), wherein governance tokens are used for decision-making processes[15].

# Blockchain Usability for Mesh Networks

![](https://miro.medium.com/max/60/0*hIwqPfXBeFLg6GGF?q=20)

![](https://miro.medium.com/max/1400/0*hIwqPfXBeFLg6GGF)

Photo by [Thought Catalog](https://unsplash.com/@thoughtcatalog?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)So how do we incentivize people to join, maintain, and grow the mesh network’s infrastructure? One possible incentive is being paid in cryptocurrency on a blockchain for routing network traffic [5].

This is where blockchain’s usability as a payment system, and smart contracts comes in handy [12]. By using the blockchain (and smart contracts) as a payment channel, nodes can determine the price of, and pay for, forwarding packets to other nodes on the network [5][12][13][14].

Additionally, we can deploy a DAO ***(ideally organized as a cooperative)*** on the blockchain to oversee the affairs of the incentivized mesh network [15][3]. The DAO will help bring distributed governance (DGov) principles and practices to the nodes on the network, thereby allowing for grater transparency in the network’s affairs, and for participatory decision-making [15][3].

Also, blockchain usability can also help advance our privacy interests because we need to know how packets (bits of data) are routed and paid for on the network, but we do not need to necessarily know the contents of the packets [5]. With blockchain, we can record and verify the routing on the network (nodes sending and receiving), without the need for inspecting the routing packets [3][5].

Possible source: [https://althea.net/documents/althea-pres.pdf](https://althea.net/documents/althea-pres.pdf)

## Disrupting Who?

Disrupting your local (not-so local), not always friendly, sometimes price-gouging, sometimes data throttling, internet service provider (ISP) such as Comcast [6][7][8][9].

# Pioneers

Althea Mesh

goTenna

Global Mesh Labs

# Greyscail Blockchain Review

![](https://miro.medium.com/max/428/0*Vjyj9NGmhFYfl1BT.png)

Greyscail Blockchain Review is a member-run Ledgerback publication focused on blockchain technology, with an emphasis on blockchain use cases (i.e., usability).

In particular, Greyscail is intended for readers to gain a greater understanding of blockchain usability in many fields and industries beyond the hype, and hopefully our readers will aid in the full realization of blockchain’s potential.

If you are passionate about blockchain, please do not hesitate to send a message inquiring about collaborating with us on an article or a research project.

Find our more about Ledgerback on our Gitbook at docs.ledgerback.coop.

# References

[1] [https://hackernoon.com/9-things-you-need-to-know-about-mesh-networks-f61a77e5751a](https://hackernoon.com/9-things-you-need-to-know-about-mesh-networks-f61a77e5751a)

[2] [https://www.nycmesh.net/blog/how/](https://www.nycmesh.net/blog/how/)

[3] [https://detroitblockchaincenter.org/incentivized-mesh-net/](https://detroitblockchaincenter.org/incentivized-mesh-net/)

[4] [https://steemit.com/cryptocurrency/@incentivizedmesh/the-case-for-incentivized-mesh-networks](https://steemit.com/cryptocurrency/@incentivizedmesh/the-case-for-incentivized-mesh-networks)

[5] [https://althea.net/documents/althea-pres.pdf](https://althea.net/documents/althea-pres.pdf)

[6] [https://arstechnica.com/information-technology/2015/06/want%C2%AD-a-lower-comcast-bill-complain-to-the-fcc/](https://arstechnica.com/information-technology/2015/06/want%C2%AD-a-lower-comcast-bill-complain-to-the-fcc/)

[7] [https://www.theverge.com/2018/6/13/17460892/comcast-internet-throttle-congestion](https://www.theverge.com/2018/6/13/17460892/comcast-internet-throttle-congestion)

[8] [https://arstechnica.com/tech-policy/2018/08/isps-want-to-be-utilities-but-only-to-get-more-money-from-the-government/](https://arstechnica.com/tech-policy/2018/08/isps-want-to-be-utilities-but-only-to-get-more-money-from-the-government/)

[9] [https://www.nycmesh.net/blog/public-access-points/](https://www.nycmesh.net/blog/public-access-points/)

[10] [https://www.nycmesh.net/blog/how/](https://www.nycmesh.net/blog/how/)

[11] [https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)

[12] [http://www.hastingslawjournal.org/wp-content/uploads/Burge-67.6.pdf](http://www.hastingslawjournal.org/wp-content/uploads/Burge-67.6.pdf)

[13] [https://www.investinblockchain.com/what-is-a-smart-contract/](https://www.investinblockchain.com/what-is-a-smart-contract/)

[14] [https://althea.net/whitepaper](https://althea.net/whitepaper)

[15] [https://blockchainhub.net/dao-decentralized-autonomous-organization/](https://blockchainhub.net/dao-decentralized-autonomous-organization/)

[16] [https://medium.com/althea-mesh/metered-bandwidth-on-althea-e366219d98a6](https://medium.com/althea-mesh/metered-bandwidth-on-althea-e366219d98a6)
