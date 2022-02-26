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