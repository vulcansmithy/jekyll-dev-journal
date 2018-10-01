---
layout: post
title:  "Blockchain, Ethereum, Smart Contract Development Notes"
date:   2018-09-28 12:53:04 +0800
categories: Blockchain Ethereum SmartContract DevNotes
---

**Proof-of-Work** - new blocks are added by miners — network participants doing computationally intensive tasks, competing against each other for the right to create a new block based on their solution, getting a certain amount of currency of this network as a reward for a successful block creation.

**Proof-of-Stake** - blocks are added by validators — network participants, competing not through performance, but through the amount of currency of the network in their accounts. They earn less, but it takes less work, too.



#### Smart Contract

- Manipulating data in blockchain is ensured by so-called **smart contracts.**
- They describe what data should be stored on blockchain and determine the set of functions for operating it.
- Performing the functions and accessing the data is done through an interface provided by every contract. This interface is generated separately from compilation stage and allows to execute the binary code.
- The data is open for all the participants of the network, its reading costs nothing as, like we’ve already said before, all the participants do have the data.
- Data is changed through transactions.
- are code which runs (along with data which is stored) within that virtual machine, i.e. on every single node. ^[Ethereum programming for web developers: a tutorial](https://codex.happyfuncorp.com/ethereum-programming-for-web-developers-a-tutorial-9c83f35f531)^
- anyone can submit code/data to this machine without the registering or asking permission. They do, however, need to pay. Every line of code and byte of storage in Ethereum has a price. ^[Ethereum programming for web developers: a tutorial](https://codex.happyfuncorp.com/ethereum-programming-for-web-developers-a-tutorial-9c83f35f531)^
- ... MetaMask injects Web3.js into each opened page, which enables you to test basic commands directly in the javascript console in the Chrome Developer Tools... ^[Dive into Ethereum Development. Part 3: User Application](https://medium.com/@rubyruby.ru/dive-into-ethereum-development-part-3-user-application-107f0a6e5190)^



#### DApp

- **DApp**  - decentralized application.
- At the moment DApp is a logic on smart contracts plus some user interface.

- In order to perform any operations on blockchain, you need internal currency*



### Tools

- [metamask.io](https://metamask.io)
- [NodeJS](https://nodejs.org/en/)
- [remix.ethereum.org](http://remix.ethereum.org)
- [Mist, Browse and use DApps on the Ethereum network](https://github.com/ethereum/mist)
- [Truffle, A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM)](https://truffleframework.com)
- [Parity, A fast and secure Ethereum client for managing accounts, tokens, and so on](https://www.parity.io/ethereum/)



### Libraries

- [ethereum.rb, Ethereum library for the Ruby language](https://github.com/EthWorks/ethereum.rb)
- [web3JS, Ethereum JavaScript API](https://github.com/ethereum/web3.js/)
- [web3JS JavaScript app API for 0.2.x.x ](https://github.com/ethereum/wiki/wiki/JavaScript-API)
- [web3JS JavaScript app API for 1.0 release](https://web3js.readthedocs.io/en/1.0/index.html)



### Ethereum Test Ether Faucet

- [Ropsten Test Network Faucet](https://faucet.metamask.io/)


### Resources

- [*Dive into Ethereum Development. Part 3: User Application](https://medium.com/@rubyruby.ru/dive-into-ethereum-development-part-3-user-application-107f0a6e5190)
- [*How To Build an Ethereum Smart Contract for a Blockchain Marketplace](https://rubygarage.org/blog/ethereum-smart-contract-tutorial)
- [*Blockchain App with Ruby](https://www.nopio.com/blog/blockchain-app-ruby/)

* [The Beginners Guide to Using an Ethereum Test Network](https://medium.com/compound-finance/the-beginners-guide-to-using-an-ethereum-test-network-95bbbc85fc1d)

* [Tools for Working with Solidity](https://dzone.com/articles/blockwatch-tools-for-working-with-solidity)

