# WE COVER

## Web3 In Metaverse Introductory guide


> What is web3?

Before we define the web3 stack, let’s attempt to define web3. There are countless definitions depending on who you ask, but to me I find this definition spot on:


Web3 is the stack of protocols that enable fully decentralized applications.

With this decentralized tech stack, we can begin building out decentralized applications which have their own set implications and characteristics.

Some of the characteristics enabled by web3 are:

- Decentralized web infrastructure
- Ownership (of data, content, and platform)
- Native digital payments
- Self-sovereign identity
- Distributed, trust-less, & robust infrastructure
- Open, public, composable back ends


While some of the applications built on decentralized tech stacks will replace their predecessors, a new paradigm of apps have also been made possible by the new primitives enabled by blockchains.

Native digital payments and public back end infrastructure – like machine learning, mobile devices, virtual reality, and other technological primitives, platforms, and building blocks – enable entirely new types of applications to be built, some that have yet to be imagined.

Does this mean that everything is going to be replaced by web3? Not necessarily. While I do think that building on a decentralized tech stack is a much better choice for certain types of applications – like almost any technical decision, it depends on what you are building.



# Table of Contents


1. [Section 1: Web1 and Web2]()

2. [Section 2: The web3 stack]()

3. [Section 3: Build projects]()

4. [Section 4: More resources]()



![Preview](https://github.com/Thenavigo/web3Inmetaverse/blob/main/web3.png/)





1. [Section 1: Web1 and Web2]() 👇

	 
```bash
	 Section 1 - Web1 and Web2
```


## Web 1.0 –

Web 1.0 refers to the first stage of the World Wide Web evolution. Earlier, there were only a few content creators in Web 1.0 with a huge majority of users who are consumers of content. Personal web pages were common, consisting mainly of static pages hosted on ISP-run web servers, or on free web hosting services. 

In Web 1.0 advertisements on websites while surfing the internet are banned. Also, in Web 1.0, Ofoto is an online digital photography website, on which users could store, share, view, and print digital pictures. Web 1.0 is a content delivery network (CDN) that enables the showcase of the piece of information on the websites. It can be used as a personal website. It costs the user as per pages viewed. It has directories that enable users to retrieve a particular piece of information. 



> Four design essentials of a Web 1.0 site include:

Static pages.
- Content is served from the server’s file system.
- Pages built using Server Side Includes or Common Gateway Interface (CGI).
- Frames and Tables are used to position and align the elements on a page.


## Web 2.0 – 

Web 2.0 refers to worldwide websites which highlight user-generated content, usability, and interoperability for end users. Web 2.0 is also called the participative social web. It does not refer to a modification to any technical specification, but to modify the way Web pages are designed and used. The transition is beneficial but it does not seem that when the changes occur. Interaction and collaboration with each other are allowed by Web 2.0 in a social media dialogue as the creator of user-generated content in a virtual community. Web 2.0 is an enhanced version of Web 1.0. 


The web browser technologies are used in Web 2.0 development and it includes AJAX and JavaScript frameworks. Recently, AJAX and JavaScript frameworks have become a very popular means of creating web 2.0 sites. 


> Five major features of Web 2.0:

- Free sorting of information, permits users to retrieve and classify the information collectively.
- Dynamic content that is responsive to user input.
- Information flows between the site owner and site users by means of evaluation & online commenting.
- Developed APIs to allow self-usage, such as by a software application.
- Web access leads to concern different, from the traditional Internet user base to a wider variety of users.



> Usage of Web 2.0 –

The social Web contains a number of online tools and platforms where people share their perspectives, opinions, thoughts and experiences. Web 2.0 applications tend to interact much more with the end user. As such, the end user is not only a user of the application but also a participant by these 8 tools mentioned below:

- Podcasting
- Blogging
- Tagging
- Curating with RSS
- Social bookmarking
- Social networking
- Social media
- Web content voting





2. [Section 2: The web3 stack]() 👇

	 
```bash
	 Section 2 - The web3 stack
```

Let’s now start diving into the web3 stack, broken into this set of categories:


- Blockchain
- Blockchain development environment
- File storage
- Off chain data protocols
- API (indexing & querying)
- Identity
- Client (frameworks and libraries)
- Oracles
- Other protocols


## Blockchain


There are countless blockchains that you can choose to build on. There is no single one that is "the best", instead you should consider the various tradeoffs between them.


One thing that is often important to me when learning something new is the idea of applying the [Pareto principle](https://en.wikipedia.org/wiki/Pareto_principle) to what I’m learning. i.e., what is the most efficient way to get the most out of that amount of time and effort. Following this idea I can gain the most traction and momentum while learning something new in the shortest amount of time.



In the Blockchain world, learning Solidity and the [EVM](https://ethereum.org/en/developers/docs/evm/) (or Ethereum Virtual Machine) might be the best bet when getting started as a blockchain developer. Using this skillset (and tech stack), you can build not only for Ethereum, but other Ethereum Layer 2s, sidechains, and even other blockchains like Avalanche, Fantom, and Celo.


That being said, Rust is beginning to become more and more popular in the blockchain world, with Solana, NEAR, Polkadot, and others having first class Rust support. You probably can’t really go wrong learning either, but for the beginner I’d say that Solidity will still be the better choice if someone asked me today.



Beyond that advice, here is an incomplete sample of blockchains that have a solid combination of technology, utility, community, momentum, and future viability:



- [Ethereum](https://ethereum.org/en/) - original smart contract platform


- ZK rollups: [ZKSync](https://zksync.io/), [Starknet](https://starkware.co/starknet/), [Hermez](https://hermez.io/) - High throughput Ethereum layer 2s, but not natively EVM compatible


- Optimistic rollups: [Arbitrum](https://offchainlabs.com/) & [Optimism](https://www.optimism.io/) - Ethereum layer 2s, EVM compatible (learn more about the differences between optimistic and ZK rollups [here](https://vitalik.ca/general/2021/01/05/rollup.html))


- [Polygon](https://polygon.technology/) - Ethereum sidechain


- [Solana](https://solana.com/)  - high throughput, inexpensive transactions, fast block times, but harder to learn than EVM (Rust)


- [NEAR](https://near.org/) - Layer 1 blockchain, can write smart contracts in Rust or Assemblyscript


- [Cosmos](https://v1.cosmos.network/) - an ecosystem of interoperate blockchains


- [Polkadot](https://polkadot.network/) - blockchain-based computing platform that enables blockchains built on top of it to execute transactions between themselves, creating an interconnected internet of blockchains


- [Fantom](https://fantom.foundation/) - EVM compatible layer 1


- [Avalanche](https://www.avax.network/) - EVM compatible Layer 1


- [Celo](https://celo.org/) - EVM compatible layer 1, designed to make it easy for anyone with a smartphone to send, receive, and store crypto


- [Tezos](https://tezos.com/) - Non EVM compatible layer 1, a lot of NFT projects are using it



When interacting with a network, you'll need to use an RPC endpoint.

There are a few ways you can do this:

- Access a public RPC endpoint
- Running your own nodes
- Accessing a node provider as a service
- Accessing a decentralized node provider as a service


Public RPC endpoints are often provided by the network, but for most production dapps you'll want to leverage your own endpoints as they are not stable or recommended for production.

There are a handful of RPC service providers out there, here are a few:


- [Infura](https://infura.io/)
- [Figment Datahub](https://datahub-beta.figment.io/) 
- [Ankr](https://www.ankr.com/) 
- [Coinbase Cloud](https://www.coinbase.com/cloud) 
- [Cloudflare](https://developers.cloudflare.com/distributed-web/ethereum-gateway/interacting-with-the-eth-gateway/) 
- [Alchemy](https://www.alchemy.com/) 
- [Genesis Go (Solana)](https://genesysgo.com/) 



There is also a web3 / decentralized solution, [Pocket Network](https://www.pokt.network/) that seems to be gaining traction.

Any of these options are probably a good bet for interacting directly with your network.


## Blockchain development environments

For EVM development, there are a few good development environments available:


- [Hardhat](https://hardhat.org/) (JavaScript) is a newer option, but one that is gaining more and more popularity. Their docs are great, the tooling and developer experience is polished, and it’s what I’ve personally been using to build dapps.

- [Truffle](https://trufflesuite.com/) (JavaScript) is a suite of tools for building and developing applications on the EVM. It’s mature, battle tested, and well documented. It’s been around for a while and many developers use it.


- [Foundry](https://github.com/gakonst/foundry) is a new Solidity development environment from Paradigm that shows a lot of promise. Key standouts are the ability to write tests in Solidity, support for fuzzing, and speed (it's written in Rust). I wrote a separate introduction to it [here](https://mirror.xyz/sha.eth/6Mn3HjrqKLhHzu2balLPv4SqE5a-oEESl4ycpRkWFsc).


- [Brownie](https://eth-brownie.readthedocs.io/en/stable/) is a Python-based development and testing framework for smart contracts for Solidity / EVM development.



For Solana development, [Anchor](https://project-serum.github.io/anchor/getting-started/introduction.html) is quickly becoming the entry-point for new developers. It provides a CLI for scaffolding out, building, and testing Solana programs as well as client libraries that you can use for building out front ends. It also includes a DSL that abstracts away a lot of the complexities that developers often run into when they get started with Solana and Rust development.



## File storage

Where do we store images, videos, and other files in web3? Storing anything that large on-chain is usually prohibitively expensive, so we probably don’t want to store them there.

Instead, we can use one of a handful of file storage protocols:


- [IPFS](https://ipfs.io/) - peer-to-peer file system protocol
		- pros: it’s reliable, well documented with a large ecosystem
		- cons: if data is not pinned it can be lost

- [Arweave](https://arwiki.wiki/) - allows you to store data permanently, paying a single transaction fee. I’m a fan of Arweave and wrote a blog post about it here.

- [Filecoin](https://filecoin.io/) - from Protocol Labs, the same team that build IPFS, it is a protocol designed to provide a system of persistent data storage. There are [a handful of ways](https://docs.filecoin.io/store/) for developers to build on Filecoin, including [web3.storage](https://web3.storage/) which is pretty nice.

- [Skynet](https://siasky.net/) - I have not yet used it in production, but have tried it out and it seems to work nicely. The API [here](https://siasky.net/developers/) looks great. I have questions like how long is the data persisted, and Skynet's interoperability with other protocols.


## Off chain data protocols

In addition to file storage and on-chain storage, you may also need to store data off-chain. You might use these types of solutions similarly to how you might use a database in a traditional tech stack, but instead they are replicated across n number of nodes on a decentralized network, and therefore more reliable (at least in theory).

A few options are:


- [Ceramic Network](https://ceramic.network/) - a decentralized, open source platform for creating, hosting, and sharing data. Ceramic also has a nice identity protocol that I’ll talk about later. Probably my favorite off-chain storage solution at the moment. [Here’s](https://twitter.com/ceramicnetwork/status/1364631929262235648) a pretty nice demo.

- [Textile ThreadDB](https://docs.textile.io/threads/) - a multi-party database built on IPFS and Libp2p. If I understand correctly, it may be going through a big API change at the moment. I’ve tried it and it shows some promise, but the docs and DX need some improvement.

- [GunDB](https://gun.eco/) - a decentralized, peer-to-peer database. Gun has been around for quite sometime and [some pretty interesting applications](https://www.starlinglab.org/challenges/) have been built with it.



In terms of maturity, my take is that the ecosystem of off-chain storage solutions is not yet where it needs to be to build out some of the more advanced use cases some developers might want. Some challenges here are real-time data, conflict detection and conflict resolution, write authorization, documentation, and general developer experience.


Integrating offchain data solutions with blockchain protocols is one of the last big hurdles we need to cross before we have a fully decentralized protocol stack capable of supporting any kind of application.


## API (indexing & querying)

There are a lot of differences in the way that we interact with and build on top of blockchains versus databases in the traditional tech stack. With blockchains, data isn’t stored in a format that can efficiently or easily be consumed directly from other applications or front ends.

Blockchains are optimized for write operations. You often hear the innovation happening centered around transactions per second, block time, and transaction cost. Blockchain data is written in blocks over the course of time, making anything other than basic read operations impossible.

In most applications, you need features like relational data, sorting, filtering, full text search, pagination and many other types of querying capabilities. In order to do this, data needs to be indexed and organized for efficient retrieval.

Traditionally, that’s the work that databases do in the centralized tech stack, but that indexing layer was missing in the web3 stack.

- [The Graph](https://thegraph.com/en/) is a protocol for iThe Graphndexing and querying blockchain data that makes this process much easier and offers a decentralized solution for doing so. Anyone can build and publish open GraphQL APIs, called subgraphs, making blockchain data easy to query.

To learn more about The Graph, check out the docs [here](https://thegraph.com/docs/en/) or my tutorial [here](https://dev.to/edge-and-node/building-graphql-apis-on-ethereum-4poa).


## Identity

Identity is a completely different paradigm in web3. In web2, authentication is almost always based on a user’s personal information. This information is usually gathered either via a form or an OAuth provider that asks the user to hand over in exchange for access to the application.

In web3, identity revolves completely around the idea of wallets and [public key cryptography](https://blog.mycrypto.com/the-basics-of-public-key-cryptography).


While the name “wallet” serves its purpose, I’ve found that people new to web3 find the terminology confusing as it relates to authentication and identity. I hope that in the future we can figure out some other way to convey what a wallet is, as it combines aspects of finance but also identity and reputation.

As a developer, you will need to understand how to access and interact with the user’s wallet and address in various ways.


At a very basic level (and a very common requirement), you might want to request access to the user’s wallet. To do this, you’ll usually be able to access the user’s wallet in the window context (web browser) or using something like [WalletConnect](https://walletconnect.com/) or [Solana’s Wallet Adapter](https://github.com/solana-labs/wallet-adapter).


For instance, if they have an Ethereum wallet available, you’ll be able to access window.ethereum. The same for Solana (window.solana), Arweave (window.arweaveWallet), and a handful of others. WalletConnect is good for mobile web and React Native as it allows users to authorize using their mobile wallets directly from the device.


If you want to handle authentication yourself, you can allow the user to sign a transaction and then decode it somewhere to authenticate the user, but this usually requires a server. [Here](https://mirror.xyz/sha.eth/i6ry1Mxez53z91ef375sMe2rO1NvK2ipACyzKA4SR9g) is an example of how that might look using an EVM wallet, and [Here](https://docs.phantom.app/integrating/sending-a-transaction#signing-and-sending-a-transaction) is an example of how to do this with Solana / Phantom.


What about managing user profiles in a decentralized way? [Ceramic Network](https://developers.ceramic.network/learn/welcome/) offers the most robust protocol and suite of tools for managing decentralized identity. They recently released [a blog post](https://blog.ceramic.network/the-next-architecture-for-building-web3-data-applications/) outlining some of their most recent updates and giving some guidelines around how all of the tools work together. I’d start there and then explore [their docs](https://developers.ceramic.network/learn/welcome/) to gain an understanding of how to start building, and consider checking out my example project [here](https://github.com/dabit3/decentralized-identity-example) that uses Ceramic [self.id](https://developers.ceramic.network/reference/self-id/).



If you want to fetch a user’s [ENS](https://docs.ens.domains/) text records, the [ensjs](https://github.com/ensdomains/ensjs) library offers a nice API for fetching user data:


```bash
	const ens = new ENS({ provider, ensAddress: getEnsAddress('1') })
	const content = await ens.name('sha.eth').getText('avatar')
```


[SpruceID](https://spruceid.com/) is also something that looks promising but I’ve yet to try it out.

Ceramic and [Spruce](https://spruceid.dev/docs/didkit/) both implement the [W3C DID](https://www.w3.org/TR/did-core/) specificiation, which itself is also something that I would consider as a building block of web3. With that being said, any centralized implementation of DIDs goes against the idea of what the specification is trying to accomplish.



## Client

As far as JavaScript frameworks go, you can really build with anything you’d like, as the client-side blockchain SDKs are mostly framework-agnostic. That being said, an overwhelming number of projects and examples are built in React. There are also a handful of libraries like [Solana Wallet Adapter](https://github.com/solana-labs/wallet-adapter) that offer additional utilities for React, so I’d say that learning or being familiar with React is going to probably be a smart move.


For client-side SDKs in Ethereum there’s [web3.js](https://web3js.readthedocs.io/en/v1.5.2/) and [ethers.js](https://docs.ethers.io/v5/). To me Ethers is more approachable and has better documentation, though web3.js has been around longer.



In Solana, you’ll probably be working with [@solana/web3.js](https://docs.solana.com/developing/clients/javascript-api) and / or [Anchor](https://project-serum.github.io/anchor/getting-started/introduction.html) . I’ve found Anchor client libraries to be my go-to for building Solana programs since I’m using Anchor framework anyway, and I’ve found it much easier to understand then @solana/web3.js.



## Oracles

Oracles allow developers access to read real-world data & external systems from within a smart contract.

For example, the majority of financial applications require knowledge of real-world data & events happening off-chain, so Oracles are especially important in DeFi.


[Chainlink](https://chain.link/) is an Oracle that enables access to real-world data and off-chain computation while maintaining the security and reliability guarantees inherent to blockchain technology.

[Flux](https://www.fluxprotocol.org/) is a cross-chain oracle that provides smart contracts with access to economically secure data feeds.


## Other protocols

[Radicle](https://radicle.xyz/) is a decentralized code collaboration protocol built on Git. It could be thought of as a decentralized version of GitHub.

[Livepeer](https://livepeer.org/) is a decentralized video streaming network. It is mature and widely used with over 70,000 GPUs live on the network.


## Wrapping up

This post will be a living document that I keep up with as I learn, experiment, and gather feedback from developers building in web3.

If you have any feedback or ideas around something I’m missing here, please reach and share your thoughts with me. It’s exciting to see all the activity happening around web3 as developers are jumping in and getting involved. While the infrastructure is still evolving, the vision of building truly decentralized protocols and applications that allow people to coordinate without having to give power and control to large companies is an important one and we’re close to making this vision a reality.




3. [Section 3: Build projects]() 👇







