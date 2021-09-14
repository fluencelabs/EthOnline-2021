# EthOnline Hackathon 2021

Welcome to the EthOnline Hackathon 2021. We are excited to join you in pushing the Web3 envelope over the next few weeks and we are looking forward to support you in turning your ideas into Web3 realities.

## About Fluence

Fluence provides the infrastructure and tools to enable decentralized compute for applications and backends on peer-to-peer networks. Nodes in the the Fluence peer-to-peer network host content-addressable services comprised of WebAssembly Interface Types (IT) modules. Aqua, Fluence's purpose-built distribute systems programming language, allows developers to seamlessly program distributed networks and compose hosted services into decentralized applications.  As as result, the Fluence platform allows you to bring peer-to-peer compute to a variety of Web3 use cases including data storage, blockchains, identity and to develop custom hosted services and workflows using the Fluence stack.

## The Prizes

In addition to the general price pool, Fluence provides named prizes in the following categories:

### Beginner Bounty -- USD 150 for the first 10 people:

Extend the Fluence Quickstart #3 https://github.com/fluencelabs/examples/tree/main/quickstart/3-browser-to-service with a word counting service.

The service should implement word counting functionality: for a given string, return the number of words in that string. The services could be implemented as a:
- Rust module compiled to WebAssembly and deployed to at least one Fluence Node. An example of a service can be found here https://github.com/fluencelabs/examples/tree/main/quickstart/2-hosted-services.
- JavaSript/TypeScript module integrated with with Fluence JS SDK. For example, see[Services in JS SDK](https://doc.fluence.dev/docs/js-sdk/3_in_depth#service-definitions) and[example of a simple calculator service in JS](https://doc.fluence.dev/docs/js-sdk/5_run_in_node#calc-app-example).

Once the service is implemented and works, you need to provide an opportunity to provide an input string, i.e., text, call the counting service with Aqua and return the word count, e.g., display the returned word count on a webpage (word count: 8 words).

### USD 2,500 Best use of Fluence compute for your dApp

Examples in this category include

* Use Fluence to power a decentralized NFT creation and storage solution using, for examples, NFT.storage. We are especially excited about using Fluence compute to dynamically update the metadata of mutable NFTs.
* Use Fluence to create a multi source DEX price oracle. We see Fluence compute at the "decenter" of querying and processing of streams to facilitate the optimal computation of buy/sell orders and routing to DExs.
* Use Fluence to capture, process and index events across multiple EVMs, e.g., Ethereum L1 and L2, for a (common) contract and store the results on Ceramic or Textile. Not unlike optimal order processing and routing, we see a need for a decentralized compute solution to make real-time transaction routing decisions for a contract available, or to be made available, across multiple EVM implementations.

### USD 2,500 Best new tooling or pattern for other developers to use Fluence

Examples in the category include

* Use Fluence to build a highly performant, decentralized network explorer. Such a solution, for example, could use an IPFS-based store capability to serve as a hot cache and Fluence to dynamically create network slices requested by users
* Port a Web3 library to Wasm IT and deploy to the Fluence network. We are especially psyched about libraries directly or indirectly supporting EVM interaction or providing middleware services to the EVM or other Web3 protocols
* Port or implement a signature signing and verification service as Wasm IT modules for Ethereum, e.g., eth_sign and sign typed data, and compatible EVM ecosystems.
* Implement and deploy Wasm IT modules to create, manage or verify Decentralized Identity (DID) or Verifiable Credentials (VC) documents and associated linked data. An implementation using BBS+ would score a lot of points

### USD 1,000 Best use of Fluence with another event sponsor

In this category, considerations are given to the use of Fluence with any one (or more) of the event co-sponsors.

## Resources

* [Fluence documentation](https://doc.fluence.dev/docs/)
* [Aqua book](https://doc.fluence.dev/aqua-book/)
* [Fluence Devcontainer](https://github.com/fluencelabs/devcontainer)
* [Fluence IPFS Apapter](https://github.com/fluencelabs/aqua-ipfs)
* [Discord](https://fluence.chat)
* [Fluence Youtube channel](https://www.youtube.com/channel/UC3b5eFyKRFlEMwSJ1BTjpbw)
* [Book A Meeting With The Team](https://calendly.com/fluencehack/)
