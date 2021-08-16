---
layout: post
title:  Chainlink - The Missing Link to Blockchain?
image:  '/assets/img/Chainlink.png'
caption: '[Image Source: chain.link/solutions]'
tags:   tech blockchain
---

*This is the first article of a 3-part series on my reflections from Smart Contract Summit 2021.*

---

Back in 2018, I started dabbling with smart contract programming, as part of due diligence working at a tech-focused VC firm in Tel Aviv. I have always been more interested in the programmatic capabilities of blockchains instead of the speculative craze from cryptocurrencies. Naturally, I’m a bigger fan of the Ethereum Virtual Machine (EVM) and not Bitcoin. Much has changed in the blockchain space over the past 3 years, and it can be challenging to keep up with new entrants in decentralized exchanges, oracles, NFTs, lending and yield aggregators amongst others. 

---

## What is blockchain’s place in society today?

[Sergey Nazarov](https://www.crunchbase.com/person/sergey-nazarov), CEO at Chainlink, astutely identified the issues with the world’s current model of brand-based trust. Inevitable misjudgment from central authorities leads to mismanaged policies for facilitating economic growth and controlling inflation. Promises of liquidity and transparency occasionally fail, evidenced by the recent systemic failures and [outages from Robinhood](https://www.cnbc.com/2021/06/30/robinhood-to-pay-70-million-for-misleading-customers-and-outages-the-largest-finra-penalty-ever.html). This points to the need for math-based trust, pivoting towards cryptographic truth empowered by blockchains. The underlying [decentralized ledger technology](https://www.mas.gov.sg/development/fintech/technologies---blockchain-and-dlt) seeks to prevent aberrant behavior from any individual entity attempting to subvert the system. 

A blockchain in and of itself does not radically change the world. Smart contracts do. The ideal smart contract bypasses the middleman, processes verified data from the real world and automatically executes the terms of agreement based on pre-defined conditions. The myriad of industry use cases extend beyond traditional finance to the supply chain ecosystem, governmental voting systems and healthcare. Smart contracts serve to reduce fraud, increase transparency and optimize efficiency. 

[insert McKinsey industry value add picture]

---

## So what is slowing the ascent of smart contracts?

There are nevertheless several roadblocks in achieving the highly prized attributes of the incumbent system - namely scalability, connectivity and speed. 

VISA claims to handle [24,000 transactions per second](https://usa.visa.com/run-your-business/small-business-tools/retail.html) (TPS) globally and possess a theoretical server capacity twice that throughput. Although blockchain devotees critique the actual measurements to be only 1700 TPS, it is still a long shot considering [Ethereum’s current throughput of 25 TPS and Bitcoin’s 7 TPS](https://alephzero.org/blog/what-is-the-fastest-blockchain-and-why-analysis-of-43-blockchains/). 

Layer-one (L1) solutions work with the main blockchain architecture, decreasing block generation time (changing hashing complexity) and increasing information capacity per block (larger block sizes). These were not as effective as intended since additional time was required to further validate new blocks in a bid to maintain the value proposition of transparency and security. Moreover, Bitcoin’s soft fork of Segregated Witness (SegWit) to increase block size had a [muted impact on its TPS](https://www.techinasia.com/talk/segwit-doesnt-work). Apart from adjusting blockchain parameters, competitors to Ethereum include EOS that is based on a distributed proof-of-stake (dPOS) consensus mechanism, with the goals of higher scalability and eliminating transaction fees. However, this leads to the trade-off of [greater centralisation, control and censorship](https://cointelegraph.com/news/eos-proves-yet-again-that-decentralization-is-not-its-priority). 

Layer-two (L2) solutions are secondary protocols and frameworks established over the blockchain architecture. State channels (Lightning Network) offload transactions off-chain; side chains (xDai) perform transactions on independent, separate blockchains and plasma or child chains (Polygon) create copies of the main blockchain. Roll-ups are side chains that bundle transactions, through either optimistic roll-ups or ZK roll-ups. The latter does not assume validity of each transaction proof by using cryptographic zero-knowledge proofs. This is indeed quite a mouthful. 

The kaleidoscope of chains for greater scalability and speed significantly contributed to the burgeoning Ethereum L2 ecosystem. That said, [fragmentation and the lack of interoperability](https://eprint.iacr.org/2019/1128.pdf) amongst these chains invariably limits composability and the potential of crowdsourced innovation. There is no strength without unity. 

[insert Ethereum L2 ecosystem picture]

Lastly, smart contracts on the main blockchain alone lack connectivity and access to real-world data required to validate the terms of agreement. Oracles are third-party services established to bridge this gap but poorly-designed oracles are prone to man-in-the-middle attacks upon validation of external data. This [“oracle problem”](https://www.mdpi.com/2078-2489/11/11/509) is partly due to the issue of greater centralization in conventional designs. 

---

## Enter hybrid smart contracts. 

Decentralized oracle networks (DONs) solve the “oracle problem” using a committee of off-chain independent oracle nodes with consensus protocols for data validation, providing greater reliability and tamper-resistance. These DONs serve to augment on-chain smart contracts with storage, computation and networking functionalities to external data sources or APIs. This profound hybrid combination with DONs has the potential to propel smart contracts towards unparalleled connectivity and scalability. 

As the world’s largest and most reliable oracle network in DeFi, [Chainlink](https://chain.link/solutions) strives to: 
1. Enable smart contracts with access to highly validated data and interoperability in global markets
2. Provide trust-minimized off-chain computation with the Keeper Network (automation bots), Off Chain Reporting (aggregating responses from oracle nodes) and Verifiable Randomness Function (secured source of randomness for NFTs and consensus protocols)
3. Interoperate the L2 ecosystem for a multi-chain future with the recently announced Cross Chain Interoperability Protocol (CCIP), allowing for new kinds of dApps ranging from NFT bridges to cross-chain collateral and yield optimization 

[insert Chainlink diagram?]

Chainlink also tackles the tension between privacy and transparency in hybrid smart contracts. Chainlink oracles can evaluate individuals and report results to insurance companies without divulging personal data. In the data marketplace, the oracle network can test the quality of the data using the buyer’s algorithm without giving access to both the actual data and algorithm for either parties. 

---

## When, if possible, will blockchain become the backbone of the economy?

At the time of writing, the cryptocurrency market capitalization is around $1.5 trillion, and DeFi market $70 billion. In contrast, the global equities market is in excess of $100 trillion and the derivatives market more than $1 quadrillion (1000 trillion). Institutional interest and adoption of blockchain has been expanding, both indirectly through hedge exposures to cryptocurrencies and directly with the likes of Google Cloud’s smart insurance, AWS Chainlink QuickStart and Swisscom’s price data feeds. 

It is equally important to also consider the environmental impact of blockchain computation, where Bitcoin’s proof-of-work approach is indubitably [energy-consuming due to mining](https://www.ft.com/content/1aecb2db-8f61-427c-a413-3b929291c8ac). Hence, attention is drawn to Ethereum 2.0 introducing a more [energy-efficient proof-of-stake consensus mechanism](https://spectrum.ieee.org/ethereum-plans-to-cut-its-absurd-energy-consumption-by-99-percent). It is imperative for policy-makers to tread the fine balance of regulation. Under-regulation leads to undesirable fraud and hacks, such as the recent [$600 million cryptocurrency heist of Poly Network](https://www.cnbc.com/2021/08/12/poly-network-hacker-behind-600-million-crypto-heist-did-it-for-fun.html). The [DAO hack of 2016](https://www2.deloitte.com/ie/en/pages/technology/articles/DAO-Attack-Analysis.html) that resulted in a controversial Ethereum hard fork requires further scrutiny too. On the other hand, over-regulation stifles innovation and should thus be calibrated without sweeping blanket rules. 

The future of blockchain with Chainlink is promising. I am by no means a LINK marine, but I will definitely be watching the DeFi space with cautious optimism.
