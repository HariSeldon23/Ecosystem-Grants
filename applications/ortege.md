# Ortege Interchain messaging protocol

- **Team Name:** Aegis Labs (Trading as Moitessier)
- **Payment Address:** 12ikyZeprc41MZVtSHbDgpkqLrbQfKkaK5zK6pYgoAYTvTjn

## Project Overview :page_facing_up:
### Overview

Ortege - Bridging Worlds, Enabling Possibilities

Ortege represents a groundbreaking cross-chain protocol designed to facilitate the seamless transfer of value and information across diverse blockchain networks.

Our mission with Ortege is to address the pressing issue of blockchain interoperability, specifically by fostering compatibility between ink! based chains and those built on Solidity, Cosmos, and Solana. This innovative solution will empower different blockchain networks to interact and exchange value, thereby unlocking unprecedented opportunities in the realms of Decentralized Finance (DeFi), Non-Fungible Tokens (NFTs), and a myriad of other blockchain applications.

By bridging these disparate blockchain ecosystems, Ortege aims to enhance liquidity, improve accessibility, and boost efficiency for users, regardless of their chosen blockchain platform.

We are seeking to construct this as a crucial part of the burgeoning ink! infrastructure. Our vision is to provide an indispensable foundation that will support and accelerate the growth and adoption of the ink! ecosystem, fostering a more interconnected and efficient blockchain landscape

### Ink! Ecosystem Impact

By constructing robust infrastructure, we aim to unlock a plethora of use cases that are currently unattainable. A prime example is the integration of Chainlink Oracle data feeds, a highly sought-after feature within new ecosystems. However, the prohibitive costs and extensive launch times often act as deterrents. With Ortege, we intend to revolutionize this process. Any ink! chain will be able to remotely access Chainlink price feeds, reaping the benefits of Chainlink without incurring exorbitant costs.

Furthermore, Ortege will facilitate the bridging of both fungible and non-fungible tokens across all supported chains, thereby enhancing the fluidity of asset transfer and interaction.

One of the unique features of Ortege is its ability to allow users to manage interchain accounts from ink! based chains. This means that users can maintain their presence within the ink! ecosystem while remotely controlling accounts on other chains, thereby offering a seamless and integrated user experience.

Our approach to building Ortege involves leveraging our existing smart contracts, originally developed for Solidity, and implementing them within the ink! framework. This strategy not only capitalizes on our established resources but also ensures a smooth transition and integration within the ink! ecosystem.

### Project Details
For an overview of the architecture please see the following:
https://miro.com/app/board/uXjVM4gLfNU=/?share_link_id=987322811617 

#### Data Models / API Specifications of the Core Functionality
The core functionality of Ortege includes several key APIs:

Messaging API: This API allows for the sending and receiving of messages between chains.
Accounts API: This API enables an account on one chain to make smart contract calls on remote chains.
Queries API: This API allows an account on one chain to make view calls on remote chains.
Warp Route API: This API enables the movement of native, ERC20, and ERC721 tokens across chains.

#### Overview of the Technology Stack
The technology stack for Ortege includes:

Ink!: The smart contract language for building the core functionality.
Ortege: The interoperability layer that allows for communication between different blockchains.
Solidity: Will be made compatible with ink! based chains through Ortege.

#### Documentation of Core Components, Protocols, Architecture
The core components of Ortege will include:

Interchain Security Modules: These modules give developers control over their security model, allowing them to configure, compose, and customize security according to the needs of their application.
Warp Routes: These routes allow native, ERC20, and ERC721 tokens to move seamlessly across chains.
Interchain Accounts: These accounts allow an account on one chain (e.g., a DAO) to make smart contract calls on remote chains.
Interchain Queries: These queries allow an account on one chain to make view calls on remote chains.
The architecture of Ortege is designed for modularity and permissionless interoperability. This architecture allows any blockchain environment, whether it is a layer 1, rollup, or app-chain, to communicate seamlessly with any other chain on which Ortege has been deployed.

Please note that this is a high-level overview and the actual implementation may involve additional components and technologies. The exact details will depend on the specific requirements of the Ortege protocol and the constraints of the ink! language and the Ortege architecture.

- Do you need an audit for the contacts? **YES**
- CATEGORY: Infrastructure 

## Team :busts_in_silhouette:

### Team members

- Justin Trollip - CEO
- Firat Akkan - COO
- Brandon Mino - Lead Smart Contract Engineer
- Sarju Hansaliya - Full stack engineer
- Bilal Corbacioglu - Full stack engineer
- Christos Salaforis - Director of Business Development
- Jose Barato - DevOps Lead
- Abdullah Bayraklilar - Product Owner

### Contact

- **Contact Name:** Justin Trollip
- **Contact Email:** justin@moitessier.io
- **Website:** Marketing website is currently being developed, but the documentation site is a bit further along https://docs.ortege.io/version1/ 

### Legal Structure

- **Registered Address:** 2/131 Morala Avenue, Runaway Bay, Gold Coast, Queensland, Australia 4216
- **Registered Legal Entity:** Aegis Labs Pty Ltd (Trading as Moitessier)

### Team's experience

Our team is composed of seasoned professionals who have been actively involved in the Decentralized Finance (DeFi) sector for over two years, primarily through our work with Pangolin Exchange. During this period, we have facilitated approximately 18 billion USD in volume, a testament to our expertise and the trust placed in us by the community.

While Pangolin Exchange continues to be a significant project for some of our team members, a dedicated subset of our team is now channeling their expertise and passion into the development of Ortege. This new venture leverages our extensive experience in DeFi and our deep understanding of the challenges and opportunities in the blockchain space.

Over the years, we have developed numerous production-grade smart contracts, which are the backbone of any DeFi application. These smart contracts have been rigorously tested and audited to ensure their security and reliability. We understand the intricacies of smart contract development and are well-versed in best practices for coding, testing, and auditing.

In addition to our smart contract expertise, we have also built open-source UI libraries and frameworks. These tools have been used to create user-friendly interfaces for DeFi applications, making them accessible and easy to use for both experienced users and newcomers to the space. Our commitment to open-source development reflects our belief in transparency and community collaboration.

Furthermore, our team has extensive experience with backend infrastructure deployments. We have built and maintained the infrastructure necessary to support a high-volume DEX like Pangolin Exchange. This includes setting up and managing servers, databases, and other backend systems, as well as implementing robust security measures to protect user data and funds.

In summary, our team brings a wealth of experience and a proven track record in DeFi development. We are confident that we have the skills, knowledge, and passion necessary to make Ortege a success

### Team Code Repos

- https://github.com/pangolindex/exchange-contracts
- https://github.com/pangolindex/interface
- https://github.com/pangolindex/components 
- https://github.com/pangolindex/sdk

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/SarjuHansaliya
- https://github.com/HariSeldon23
- https://github.com/bmino
- https://github.com/Shungy
- https://github.com/prodesert22
- https://github.com/josedev-union

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/shane-mccann-394a8425/
- https://www.linkedin.com/in/justintrollip/
- https://www.linkedin.com/in/firat-akkan/

## Development Status :open_book:

Our project, Ortege, has made significant strides in its development phase. We have successfully deployed our backend system in a Kubernetes environment, which includes the operation of validators and relayers. This robust infrastructure ensures the smooth and secure functioning of our protocol.

In the spirit of decentralization and resilience, we have designed our system to allow for the deployment of additional validators by any party. This feature enhances the security and reliability of our protocol by preventing any single point of failure and promoting a more distributed network.

We have also made substantial progress on the smart contract front. Our team has deployed smart contracts onto EVM chains and achieved key milestones, including the successful transmission of interchain messages, the creation of a bridge for tokens, and the ability to remotely read state on smart contracts. These accomplishments demonstrate our technical prowess and the functional capabilities of our protocol.

To provide transparency and traceability, we have deployed an explorer that can track the entire lifecycle of a message. This tool allows users to monitor the status of their transactions and provides valuable insights into the operation of the protocol.

Lastly, we have integrated WalletConnect 2 to enable the remote control of an interchain account on another chain. This feature enhances the user experience by allowing users to manage their assets across different chains from a single interface.

In summary, while there is still work to be done, we are proud of the progress we have made so far and are excited about the potential of Ortege to revolutionize blockchain interoperability.

## Development Roadmap :nut_and_bolt:

### Overview
- **Total Estimated Duration:** 5 months
- **Full-Time Equivalent (FTE):**  4 FTE
- **Total Costs:** $225,000

### Milestone 1 Ink! Smart Contracts
We will begin by developing smart contracts in the ink! language. These contracts will form the backbone of our protocol, enabling the core functionality of cross-chain communication. We will leverage the design principles and specifications provided by Hyperlane to ensure our contracts are robust, secure, and efficient. This will involve creating contracts for managing the protocol's state, handling message routing, and facilitating the transfer of value across chains.

- **Estimated duration:** 2 months
- **FTE:**  2
- **Costs:** 75,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0  |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can query, call or post an interchain message. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article** that explains all the smart contracts developed as well as how to interact with them |
| 1. | Smart contract: Message | The message is the core data structure used by the Ortege protocol. It is a packed data structure that contains all the information needed to route a message from one domain to another. |
| 2. | Smart contract: Mailbox | The mailbox is the entrypoint for developers to send and receive messages from. |
| 3. | Smart contract: Interchain Security Module | Interchain security modules are used to verify messages before they are processed. |
| 4. | Smart contract: Interchain Gas Paymaster | The gas paymaster is used to pay for the gas required in message processing on the destination chain. This is not strictly required if relayers are willing to subsidize message processing. |


### Milestone 2 Agents compatible with Substrate RPC endpoints

- **Estimated Duration:** 2 month
- **FTE:**  2
- **Costs:** 75,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0  |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how an agent can index messages as well as how a validator can sign a checkpoint and how relayers can relay messages. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article** that explains all the agents developed as well as how to interact with them |
| 1. | Agent: Message indexing | All agents must index messages from the origin mailbox. For ink! we'll need to emit events and then have the agents to get the the message content reliably and with consistent ordering. |
| 2. | Agent: Validator | In addition to indexing messages dispatched from the mailbox, validators produce attestations for the messages they observe to be used on the destination chain for security. |
| 3. | Agent: Relayer | In addition to indexing messages dispatched from the mailbox, relayers process messages on the destination chain. This requires building metadata that satisfies the message recipient's ISM (Interchain Security Module) verification requirements, and signing transactions that process the message on the destination mailbox. |

### Milestone 3 Warp Routes and Chainlink Integration

- **Estimated Duration:** 3 month
- **FTE:**  4
- **Costs:** 75,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0  |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can permissionlessly create their own Warp Route and how they can use an ink! smart contract to remotely read a Chainlink feed |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article** that explains all the smart contracts developed as well as how to interact with them |
| 1. | Application: Warp Route | We will deploy a sample Warp Route for sending ETH from Ethereum to an ink! enabled chain. |
| 2. | Smart contract: Chainlink AggregatorV3Interface | We will deploy an ink! smart contract that replicates the functionality of Chainlinks AggregatorV3Interface https://docs.chain.link/data-feeds/api-reference |

## Future Plans

While our immediate focus is on enabling interoperability between ink! chains and Solidity-based chains, we are mindful of the broader landscape of blockchain platforms. Specifically, we recognize the growing importance and popularity of Cosmos and Solana in the blockchain ecosystem.

However, it's important to note that the integration of Cosmos and Solana is currently out of scope for this particular phase of our project. This decision is primarily due to the fact that Hyperlane, whose codebase and architecture we heavily rely on, is still in the process of developing functionality for these platforms.

That being said, we are closely monitoring Hyperlane's progress in this area. As soon as their Cosmos and Solana functionality is production-ready, we plan to extend our protocol to support these platforms as well. This will allow ink! chains to connect not only to Solidity chains, but also to Cosmos and Solana, further enhancing the interoperability and versatility of our protocol.

In the long term, our vision is for Ortege to become a universal bridge between all major blockchain platforms, enabling seamless communication and value transfer across the entire blockchain ecosystem. We believe this will open up new possibilities for decentralized applications and contribute to the growth and maturation of the blockchain industry.

## Additional Information :heavy_plus_sign:

**How did you hear about the Bounty Program?** Astar team mentioned it to us