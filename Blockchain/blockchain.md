# Blockchain

<p align="center"><img height="150" src="https://cdn-images-1.medium.com/max/770/1*cCM-v2LMlWmhibkqu705Qg.png"></p>

Blockchain is a system in which a record of transactions made in bitcoin or another cryptocurrency is maintained across several computers that are linked in a peer-to-peer network.

# Table of Contents

- [Crash Course](#crash-course)
- [White Papers](#white-papers)
- [Talks](#talks)
- [Solidity](#solidity)
- [Ethereum](#ethereum)
- [Setup](#setup)
- [Hyperledger](#hyperledger)

### Crash Course

- [Blockchain 101 - A Visual Demo](https://www.youtube.com/watch?v=_160oMzblY8) - Youtube
- [Blockchain Specialization](https://www.coursera.org/specializations/blockchain) - Coursera
- [Bitcoin and Cryptocurrency Technologies ](https://www.coursera.org/learn/cryptocurrency) - Princeton University
- [Bitcoin](https://www.khanacademy.org/economics-finance-domain/core-finance/money-and-banking/bitcoin/v/bitcoin-what-is-it) - Khan Academy Series
- [Crypto Currencies, the Blockchain, and Smart Contracts](https://crypto.stanford.edu/cs251/) - Standford
- [Ethereum Developer: Build A Decentralised Blockchain App](https://www.udemy.com/ethereum-developer/) - Udemy
- [The Basics of Blockchain: A Beginner's Guide to Blockchain](https://www.udemy.com/the-basics-of-blockchain/) - Udemy
- [Ethereum Blockchain Developer Bootcamp With Solidity](https://www.udemy.com/course/blockchain-developer/) - Udemy
- [Introduction to Digital Currencies](https://www.unic.ac.cy/blockchain/free-mooc/) - University of Nicosia

### White papers

- [A brave new world? What impact will distributed ledger technology have on the financial industry?](https://www.ecb.europa.eu/paym/pdf/infocus/20160422_infocus_dlt.pdf) - The European Central Bank
- [Banking in a world of programmable assets](https://www.accenture.com/t20160509T223022__w__/us-en/_acnmedia/PDF-16/Accenture-Strategy-Banking-World-of-Programmable-Assets.pdf) - Accenture
- [A Fistful of Bitcoins: Characterizing Payments Among Men with No Names](http://cseweb.ucsd.edu/~smeiklejohn/files/imc13.pdf) - University of San Diego California
- [BlockChain Technology Beyond Bitcoin](http://scet.berkeley.edu/wp-content/uploads/BlockchainPaper.pdf) - University of California, Berkeley
- [An Architecture for the Internet of Money](https://docs.google.com/document/d/1Bc-kZXROTeMzG6AvH7rrTrUy24UwHoEcgiL7ALHMO0A/pub) - Meher Roy

### Talks

- [Beyond Bitcoin - Block Chains and the Future of Trustless Computing](https://www.youtube.com/watch?v=IgETC2JMUBI)
- [Bitcoin Is Exciting Because It's Cheap](https://www.youtube.com/watch?t=26&v=DyAufA2lWn0) - Bill Gates
- [Everything You Need to Know About Bitcoin](https://www.youtube.com/watch?v=SNssKmeXrGs) - Reihan Salams
- [How Cryptocurrencies Can Succeed: the Stripe Perspective](https://www.youtube.com/watch?v=6qZwl7mukZ8) - Greg Brockman
- [How the Blockchain is Changing Money and Business](https://www.ted.com/talks/don_tapscott_how_the_blockchain_is_changing_money_and_business?language=en) - Don Tapscott
- [Internet vs Bitcoin ](https://www.youtube.com/watch?v=s0luLPVHkO4)
- [Join The Bitcoin Revolution](https://www.youtube.com/watch?v=24ce5tV-pgg)
- [TEDx, Cryptocurrencies like Bitcoin are coming, and it's a good thing](https://www.youtube.com/watch?v=0GL9PTQiqxw) - Juan Llanos
- [Powerful Technology Transforming Society](http://www.youtube.com/watch?v=YIVAluSL9SUA)
- [Quick Introduction to Bitcoin](https://www.youtube.com/watch?v=slFuj5N4twc)
- [TEDx, Distributing Power & Trust](https://www.youtube.com/watch?v=WI1pbHi1fww) - Eric Spano
- [The Future of Bitcoin: New Applications and Rebuilding the banking system: (28min)](https://www.youtube.com/watch?v=mD4L7xDNCmA) - Mike Hearn
- [The future will be decentralized](https://www.youtube.com/watch?v=97ufCT6lQcY) - Charles Hoskinson
- [Xapo, the history of money](http://youtu.be/IP0jCjyrew8)

### Solidity

Solidity is the most popular language on Ethereum, inspired by C++, Python, and JavaScript

- [Documentation](https://solidity.readthedocs.io/en/v0.6.10/)
- [Cheat Sheet](https://reference.auditless.com/cheatsheet/)
- [Github](https://github.com/ethereum/solidity/)
- [Solidity for beginers](https://www.tutorialspoint.com/solidity/index.htm)
- [Solidity Tutorial - A Full Course on Ethereum, Blockchain Development, Smart Contracts, and the EVM](https://www.youtube.com/watch?v=ipwxYa-F1uY)
- [Solidity](https://ethereumbuilders.gitbooks.io/guide/content/en/solidity_tutorials.html)

### Ethereum

Ethereum is an open-source, blockchain-based, decentralized software platform used for its own cryptocurrency, ether. It enables SmartContracts and Distributed Applications (DApps) to be built and run without any downtime, fraud, control, or interference from a third party.

- [Ethereum whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
- [Ethereum course (highly recommended)](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/)
- [Learn Dapp development by coding your own game](https://cryptozombies.io/)
- [Blockchain: Foundations and Use Cases](https://www.coursera.org/learn/blockchain-foundations-and-use-cases)
- [Hand-on course by DApp University](https://www.youtube.com/playlist?list=PLS5SEs8ZftgWFuKg2wbm_0GLV0Tiy1R-n) - Youtube playlist
- [Course on Coursera](https://www.coursera.org/learn/blockchain-basics)
- [Ethereum 101, Parts: 1-7](https://kauri.io/ethereum-101/5bb65f0f4f34080001731dc2/c)

## Ethereum Set-up

**Requisites for Ethereum setup**

**Installing npm package**

- before npm install node.js

```
wget -qO- https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```

- now install npm

```
brew install node
```

- **truffle ganache** framework
  - download .appimage file from [ganache](https://truffleframework.com/ganache)
  ```
  cd ~/Downloads
  chmod a+x <.appimage filename>
  ./<.appimage filename>
  ```
- Metamask Chrome Extension - to live track transactions on the Ethereum test network
  [Metamask Website](https://metamask.io/)
- Sublime text package highlighting for solidity language

- Remix is a Web-based IDE with built-in static analysis, and a test blockchain virtual machine
  [Remix](https://remix.ethereum.org/)

## Hyperledger

### Hyperledger fabric

Hyperledger Fabric is intended as a foundation for developing applications or solutions with a modular architecture. Hyperledger Fabric allows components, such as consensus and membership services, to be plug-and-play. Its modular and versatile design satisfies a broad range of industry use cases. It offers a unique approach to a consensus that enables performance at scale while preserving privacy.

- [Getting started](https://hyperledger-fabric.readthedocs.io)
- [Fabric samples - Chaincode, SDKs and Network setup](https://github.com/hyperledger/fabric-samples)
- [Hyperledger tutorials and articles](https://medium.com/coinmonks/top-hyperledger-tutorials-and-articles-b77cf3e4d1eb)
- [Linux foundation free course on Hyperledger Technologies](https://training.linuxfoundation.org/training/blockchain-for-business-an-introduction-to-hyperledger-technologies/)
- [Udemy course on Hyperledger](https://www.udemy.com/hyperledger/)
- [IBM hyperledger fabric](https://www.ibm.com/blockchain/hyperledger)
- [Course by linux foundation](https://www.edx.org/course/blockchain-for-business-an-introduction-to-hyperledger-technologies)

### Hyperledger Composer

Hyperledger Composer is an extensive, open development toolset and framework to make developing blockchain applications easier.

- [Getting started](https://hyperledger.github.io/composer/latest/tutorials/tutorials.html)
- [Online playground](https://composer-playground.mybluemix.net/)
