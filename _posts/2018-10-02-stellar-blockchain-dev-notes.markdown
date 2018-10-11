---
layout: post
title:  "Stellar Blockchain Research Notes"
date:   2018-10-02 14:22:16 +0800
categories: article researchnotes
---

- [Stellar (payment network), Wikipedia](https://en.wikipedia.org/wiki/Stellar_(payment_network))
- > Every Stellar account has a public key and a secret seed. [*](https://www.stellar.org/developers/guides/get-started/create-account.html)

- > The public key is always safe to share.. [*](https://www.stellar.org/developers/guides/get-started/create-account.html)

- > The seed, however, is private information that proves you own your account. You should never share the seed with anyone. [*](https://www.stellar.org/developers/guides/get-started/create-account.html)

- > If you’re familiar with public key cryptography, you might be wondering how the seed differs from a private key. The seed is actually the single secret piece of data that is used to generate both the public and private key for your account. Stellar’s tools use the seed instead of the private key for convenience: To have full access to an account, you only need to provide a seed instead of both a public key and a private key. [*](https://www.stellar.org/developers/guides/get-started/create-account.html)

- **Lumens**, the native Stellar tokens...

- Anchors are entities in the Stellar network which can hold a deposit and issue credits as and when required.

- [**Anchors** ], They act as a bridge between different currencies and the Stellar network

- All money transactions in the Stellar network (except the native digital currency of lumens) occur in the form of credit issued by [**Anchors** ].

- Stellar was released as a decentralized payment network and protocol with a native currency, stellar

- The Stellar Development Foundation released an upgraded protocol with a new consensus algorithm in April 2015 which went live in November 2015

- The new algorithm used SCP, a cryptocurrency protocol created by Stanford professor David Mazières. 

- The consensus process happens at a regular interval, typically every 2 to 4 seconds

- Anchors are simply entities that people trust to hold their deposits and issue credits into the Stellar network for those deposits. 

- They act as a bridge between different currencies and the Stellar network

- All money transactions in the Stellar network (except the native digital currency of lumens) occur in the form of credit issued by anchors

- Regulatory compliance

- Each transaction on the network costs a small fee: 100 stroops (0.00001 XLM). This fee helps prevent bad actors from spamming the network.

- [Stellar.org](http://stellar.org/) operates a small test network and Horizon instance.

- > Keep in mind that you can always run your own test network for use cases that don’t work well with SDF’s testnet. [*](https://www.stellar.org/developers/guides/concepts/test-net.html)

- > When you hold assets in Stellar, you’re actually holding credit from a particular issuer. The issuer has agreed that it will trade you its credit on the Stellar network for the corresponding asset–e.g., fiat currency, precious metal–outside of Stellar. [*](https://www.stellar.org/developers/guides/concepts/assets.html#trustlines)







### Tools

- [stellar/ruby-stellar-sdk](https://github.com/stellar/ruby-stellar-sdk)



#### Stellar Smart Contracts

- *****[First impressions at creating Stellar Smart Contracts](https://medium.com/coinmonks/first-impressions-at-creating-stellar-smart-contracts-d51f18552bbc) and [Simple Escrow Contract using Stellar](https://medium.com/coinmonks/simple-escrow-contract-using-stellar-67aa799f7db)
- *****[I Just Wrote a Stellar Smart Contract](https://medium.com/@robdurst/i-just-wrote-a-stellar-smart-contract-7f54a391f5e1) and [I Just Wrote a Stellar Smart Contract Pt. 2: Let’s Dig a Little Deeper](



### Notable Links

- [* Stellar Developers Documentation](https://www.stellar.org/developers/)

- [*github.com/stellar](https://github.com/stellar)

- [*Stellar Consensus Protocol by Prof. David Mazières](https://www.stellar.org/papers/stellar-consensus-protocol.pdf)

- [*Tokens on Stellar](https://www.stellar.org/blog/tokens-on-stellar/)

- [* **Testnet** is a small test Stellar network, run by the Stellar Development Foundation (SDF), which is open to developers.](https://www.stellar.org/developers/guides/concepts/test-net.html)

- [Stellar docker image](https://hub.docker.com/r/stellar/quickstart/)

- [Stellar vs. Ethereum – A Comprehensive Guide](https://unblock.net/stellar-vs-ethereum/)

- [What is Stellar? (XLM), Youtube](https://www.youtube.com/watch?v=mB9UW7HK8pc/)

- [Stellar Lumens in a Nutshell, Youtube](https://www.youtube.com/watch?v=20gwXDQi55w)

- [Smart contracts - Simply Explained, Youtube](https://www.youtube.com/watch?v=ZE2HxTmxfrI)

- [*Deep Dive Into Stellar (XLM), Youtube](https://www.youtube.com/watch?v=o_w2MjEs4Ww)

- [Stellar Javascript SDK #1 - Introduction and Information Sources, Youtube](https://www.youtube.com/watch?v=bpiSYjrNDog)

- [Horizon: API webserver for the Stellar network, Youtube](https://www.youtube.com/watch?v=AtJ-f6Ih4A4)






