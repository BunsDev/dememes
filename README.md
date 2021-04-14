# DeMemes.app | Decentralized Memes on IPFS: A Simple Tutorial

## Soft Introduction to IPFS
This tutorial is designed to enable users to learn how to incorporate both Ethereum and IPFS to build an application that enables users to upload files to [IPFS](https://ipfs.io/), which is "a peer-to-peer hypermedia protocol designed to make the web faster, safer, and more open". 

In short, a decentralized file storage system. This tutorial may be forked for users who are interested in discovering how to spin the Meme of the Day application to a more practical use-case, such as the storage of files that are designed to be publicly accessible and immutable, which is just another way of saying "unable to be altered (changed) by anyone". **There are NO pre-requisites for this tutorial. Everyone is welcome to learn from this tutorial.**

## Why IPFS?
IPFS is designed to operate as a single source of truth in the sense that it contains the content itself and not just the location of the content. For example, if you were to open an image named `kittens.jpeg` you would anticipate viewing a cute kitten, but you may have actually just opened a photo of a rotten apple instead. As such, the name of the file does not tell you anything. If you were to, instead, search for an IPFS hash, you would discover the source you are in search of and you will know the contents of 100% of the time before even opening it with 100% certainty. 

**Why?** Because once a hash is created, it is immutable, so it cannot change. The only thing it can do is be erased by whoever is storing (hosting) the associated file. The file is broadcasted and shared by a bunch of servers connected to IPFS. These servers cannot change the content, even the creater cannot change the content. Why? Because any alterations to the content would result in a different hash. IPFS uses hashes, so when you upload the file, it is identifed by its hash. This application is designed to enable you to upload an image, generate an IPFS hash, which is then stored on the blockchain.

**Why not use just use Ethereum?**
Ethereum alone would be an expensive solution as it is structured in a manner that requires all nodes to keep a copy of the entire blockchain. The reason why transaction fees exist is to compensate for the computational costs associated with making this copy. As such, storing files on Ethereum would be cost-prohibitive. As such, IPFS offers a viable solution as the nodes are designed to distributed file, which is not the intended design of Ethereum.

## Questions or Concerns?
Contact me via [Telegram](https://t.me/crypto_unico) or [Twitter](https://twitter.com/cryptounico) and I will reply to anyone willing to learn and grow as a blockchain developer (free of charge). Please be patient as I tend to be busy working on a myriad of projects at any given moment, but you may expect a reply within a week. If you do not hear back within a week, do not hesitate to message me a kind reminder as it is likely you were lost in the crowd unintentionally.


<br>

---
# Installation and Setup Instructions

<br>

1. Install Dependencies
```
yarn install
```

2. Compile Smart Contracts
```
yarn compile 
```

3. Truffle Migrations
```
yarn migrate
```
3. Test Smart Contracts
```
yarn test
```

## Truffle Console Commands

Define meme
```
const meme = await Meme.deployed()
```
Define memeHash
```
let memeHash = await meme.get()
```

Acquire Meme Address
```
memeHash = await meme.get()
```
Create memeHash
```
memeHash = 'abc123'
```
<br>
---
## Downloads - Documentation - Tutorials
---
<br>

- [NodeJS Download](https://nodejs.org/en/download/)
- [Ganache Download](https://www.trufflesuite.com/ganache)
- [Truffle Overview](https://www.trufflesuite.com/docs/truffle/overview)
- [ReactJS Tutorial](https://reactjs.org/tutorial/tutorial.html)
- [Infura IPFS Docs](https://infura.io/docs/ipfs)
- [Mocha Docs](https://mochajs.org/#getting-started)
- [Chai Docs](https://www.chaijs.com/guide/)
- [YouTube Tutorial](https://www.youtube.com/watch?v=pTZVoqBUjvI)
