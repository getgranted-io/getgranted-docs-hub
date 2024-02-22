---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🔖 Web3 Glossary

## Blockchain

### **Layer 0 (L0)**

Layer 0 (L0) blockchains serve as the foundational infrastructure in the blockchain architecture,  providing the necessary infrastructure for launching multiple Layer 1 networks, each tailored for specific tasks and addressing scalability challenges, enabling Layer 1 networks to communicate and interact seamlessly. Layer 0 architecture typically includes a main chain that stores transaction data from various Layer 1 chains and independent Layer 1 networks known as sidechains, which run their consensus mechanisms but may share the security features of the main chain and allow for secure and efficient data and token transfers between different blockchains in the Layer 0 ecosystem.

### **Layer 1 (L1)**

Layer 1 (L1) blockchains are the foundational networks in the blockchain ecosystem, responsible for processing and validating transactions, maintaining consensus, and supporting smart contracts and decentralized applications (dApps). These standalone networks face scalability challenges, which they address through various innovations such as sharding and consensus mechanism upgrades. Examples include Ethereum, SKALE, and Tezos, each offering unique capabilities that underpin various applications, from financial services to digital collectibles. As the core of decentralized technology, L1 blockchains are essential for ensuring transaction integrity, security, and the decentralized nature of the blockchain, serving as the backbone for a growing digital economy and the development of higher-layer solutions.

### **Layer 2 (L2)**&#x20;

Layer 2 solutions are built on top of Layer 1 blockchains and are designed to enhance scalability and efficiency. They achieve this by handling a portion of the transactional workload off the main chain, thereby reducing congestion. L2 solutions include rollups, state channels, and nested blockchains. Rollups bundle multiple transactions and validate them before submitting them to the main chain as a single transaction. State channels allow two-way communication for transactions off the main chain. Nested blockchains involve secondary chains working under the main chain's rules, handling day-to-day transactions and reporting to the main chain only for finalization or dispute resolution. Examples of Layer 2 solutions are the Bitcoin Lightning Network, Ethereum's Raiden, and platforms like Optimism and Arbitrum, which use rollup technology​​​​.

### **Layer 3 (L3)**

Layer 3 focuses on interoperability between different blockchain networks and is designed to enhance the scalability of blockchain networks beyond the capabilities of L1 and L2. It offers an infrastructure for developing more complex decentralized applications (dApps) that require advanced features and functionalities.

### **Layer 4 (L4)**

Layer 4 is where most decentralized applications (dApps) run, using smart contracts to execute their business logic​. It is often called the application or user interface layer in the blockchain architecture. It represents the entry point for users into the blockchain ecosystem, providing user-friendly interfaces and interactions with the underlying blockchain technology.

### **Sidechains**

Sidechains are independent blockchain networks that link to a parent blockchain (like Bitcoin or Ethereum) through a two-way peg. They have consensus protocols and can operate independently, improving privacy and security. The critical feature of sidechains is their ability to facilitate the transfer of digital assets between the mainnet and the sidechain, allowing users to move assets across networks seamlessly. They essentially expand the capabilities of the leading blockchain by allowing more experimental or niche applications without overburdening the leading network​​while still being linked to the network's ecosystem and security.

### **Yield Farming**

Users can stake their on-chain assets, such as tokens or in-game assets (NFTs), to earn additional rewards.

### **Decentralized Autonomous Organizations (DAOs)**

Users collectively govern network/application roadmap decisions and management assets through community governance.

***

## NFTs

### **ERC-721 NFTs**

ERC-721 is a standard for NFTs on the Ethereum blockchain. Each ERC-721 token is unique and cannot be exchanged on a one-to-one basis with other tokens. These NFTs are often used to represent ownership of digital or physical assets, such as artwork, collectibles, virtual real estate, and more.

### **ERC-1155 NFTs**

ERC-1155 is another standard for NFTs on the Ethereum blockchain, designed to be more flexible than ERC-721. ERC-1155 tokens can represent both fungible and non-fungible assets within a single contract. A single ERC-1155 contract can handle multiple NFTs, offering developers greater efficiency and versatility.

**Key Differences:**

* **Uniqueness vs. Multi-Fungibility:** ERC-721 tokens are unique and non-fungible, meaning each token has distinct properties or attributes. ERC-1155 tokens can be non-fungible and fungible within the same contract, allowing developers to create various token types in a single deployment.
* &#x20;**Efficiency and Gas Costs:** ERC-1155 is often considered more gas-efficient than ERC-721, as it allows for managing multiple token types in a single contract. This can result in cost savings for developers and users when interacting with these tokens on the Ethereum blockchain.
* **Due to their standardization and popularity, the Interoperability ERC-721 tokens are widely supported by NFT marketplaces, wallets, and applications**. While ERC-1155 tokens offer more flexibility in creating custom token types, adoption may vary across platforms.

**Metadata and Attributes:** Both ERC-721 and ERC-1155 tokens can include metadata and attributes to provide additional information about the assets they represent. This information is often used for display and interaction purposes in NFT applications.

**Smart Contract Complexity:** ERC-721 contracts tend to be simpler, as they deal with individual unique tokens. ERC-1155 contracts can be more complex due to handling multiple token types, but they offer a single contract solution for managing diverse assets.

**Batch Operations:** ERC-1155 allows batch operations, making it more efficient for performing actions on multiple tokens at once, which can be especially useful in gaming scenarios.

### **ERC-998 Composable NFTs**

ERC-998 is an extension of ERC-721 that enables the creation of composable NFTs. These NFTs can hold other NFTs or fungible tokens, creating nested ownership structures. It's often used for complex in-game items and assets in blockchain-based games.

### **ERC-20 and NFT Bridges**

Some projects have developed bridges or standards to convert ERC-20 tokens (fungible tokens) into NFTs and vice versa. This innovation allows for unique fungible tokens or fractional ownership of NFTs.

### **Fractional Ownership**

Fractional ownership is achieved by dividing an NFT into smaller, tradable units, often as fungible blockchain tokens. These fungible tokens, sometimes called "NFT shares" or "NFT fractions," can be bought, sold, and traded like regular tokens.&#x20;

**Benefits of Fractional Ownership:**

* **Access to High-Value NFTs:** Fractional ownership democratizes access to high-value NFTs that may be out of reach for individual buyers. Investors can pool their resources to own prestigious NFTs collectively.
* **Liquidity and Trading:** Fractional ownership tokens can be freely traded on secondary markets, providing liquidity to NFT investors. This allows token holders to exit their investments or trade their shares more easily.
* **Collective Decision-Making:** Token holders often participate in governance decisions regarding the NFT. This can include voting whether to sell the NFT, display it in a virtual gallery, or use it in a decentralized application (dApp).
* **Reduced Risk:** Fractional ownership can mitigate the risk of investing in a single NFT. If the NFT's value fluctuates, the impact on each token holder is proportionate to their ownership share.

**Use Cases and Applications:**

* **Art Ownership:** Fractional ownership allows multiple art enthusiasts to collectively own valuable digital artworks, granting them the right to display the artwork in their virtual galleries or sell their shares.
* **Real Estate and Virtual Land:** In virtual worlds and metaverse platforms, fractional ownership can apply to virtual real estate or land parcels, enabling shared ownership of virtual properties.
* **Music Royalties:** Musicians and creators can tokenize ownership of their music rights and distribute them among investors, allowing for shared revenue from music sales and royalties.
* **Collectibles and Rare Items:** High-value collectibles and rare in-game items can be fractionalized, making them more accessible to a broader audience of collectors and gamers.

It's important to note that the implementation of fractional ownership may vary depending on the blockchain platform and the specific smart contract used. Additionally, regulatory considerations may apply, so participants should be aware of legal requirements and tax implications related to fractional ownership of NFTs in their respective jurisdictions.

### Stateful NFTs

Stateful NFTs, also known as "Smart NFTs" or "Interactive NFTs," are a type of non-fungible token (NFT) that goes beyond static digital assets. Unlike traditional NFTs, which primarily represent ownership of a unique item or piece of content, stateful NFTs can change, adapt, or respond to various inputs, conditions, or interactions. Here are key characteristics and examples of stateful NFTs:

**Characteristics of Stateful NFTs:**

1. **Programmability:** Stateful NFTs are programmable and contain embedded code or smart contracts that enable them to perform specific actions or respond to triggers.
2. **Interactivity:** These NFTs can interact with external data sources, user inputs, or other smart contracts, allowing them to change their behavior or appearance in real time.
3. **Dynamic Attributes:** Stateful NFTs can have dynamic attributes or properties that can be modified or updated over time. These attributes can affect the NFT's appearance, functionality, or value.
4. **Utility and Functionality:** Stateful NFTs often have utility or functionality beyond simple ownership. They can represent access rights, memberships, or in-game items in decentralized applications (dApps) or virtual worlds.

**Examples of Stateful NFTs:**

1. **Virtual Pets:** Stateful NFTs can represent virtual pets or creatures that require care and interaction. Owners may need to feed, play with, or train their virtual pets to make them grow or gain new abilities.
2. **In-Game Items:** In blockchain-based games, stateful NFTs can be in-game items with attributes, abilities, and durability. For example, a sword NFT could level up and become more powerful through use in the game.
3. **Art and Music NFTs:** Interactive art or music NFTs can change their appearance or play different compositions based on external factors like time of day, weather conditions, or user interactions.
4. **Collectible Cards:** Stateful NFTs can represent collectible cards that evolve or gain new abilities over time, creating dynamic gameplay experiences in blockchain card games.
5. **Virtual Real Estate:** Virtual land NFTs can have stateful features, such as building structures or generating resources over time. Owners can develop their virtual properties within decentralized metaverse platforms.
6. **Membership and Access Tokens:** Stateful NFTs can serve as membership or access tokens to exclusive communities, events, or content. Ownership of these NFTs grants privileges and access to specific areas or features within a platform or ecosystem.
7. **Dynamic Art and Stories:** Interactive artworks or narratives can change based on user interactions or external data, offering unique storytelling experiences through NFTs.
8. **Utility Tokens:** Some NFTs act as utility tokens within dApps or platforms, enabling specific actions or functions, such as voting, governance participation, or resource allocation.

### Soulbound Tokens (SBT)

Soulbound Tokens (SBTs), introduced by Ethereum's Vitalik Buterin and others, are non-transferable tokens representing personal identities, credentials, and affiliations in a decentralized society (DeSoc). Unsellable and non-financialized, they aim to enhance trust and governance in Web3, with applications in DAOs, KYC, credit scoring, and combating online bots. Like the metaverse, SBTs are pivotal in blending physical and virtual realities by symbolizing human interactions. However, they face challenges like wallet recovery, potential misuse as a social credit system, and ethical issues in reputation-based societies. As a developing concept, SBTs hold promise for shaping the future of Web3 and decentralized communities, balancing technological innovation with social identity and community dynamics. SBTs can be used to represent and verify personal credentials, achievements, and affiliations, enhancing trust and collaboration in digital communities; they are applicable in DAO governance, allowing for delegated authority based on verified attributes, can be instrumental in KYC processes, credit scoring systems, and combating bots and spam in online environments, and more!

### **NFT Drops**

Exclusive Non-Fungible Token (NFT) assets are distributed to users/players as rewards.

### **NFT Marketplaces**

Integration with NFT marketplaces like OpenSea or Rarible for trading on-chain assets.

## NFT Use-Cases

### Trial/Ephemeral NFTs

Ephemeral or Trial Utility NFTs are a novel concept in the NFT space that allows for temporary access to digital content through NFTs. These NFTs are particularly suited for Free-to-Play games and adopt a 'Try before Buy' approach. Unlike traditional NFTs, Ephemeral NFTs come with an expiration date or limited use, introducing a dynamic aspect to digital ownership. This model enables unique time-bound experiences within the NFT ecosystem, enhances user engagement through limited-time access, and facilitates financial inclusion by allowing users to experience premium features without a complete purchase. Ephemeral NFTs can be applied in various fields, such as gaming, art, and culture, and are seen as a way to introduce scarcity and increase the perceived value of digital assets. See [ERC-7066](https://eips.ethereum.org/EIPS/eip-7066), which pertains to creating and handling NFTs with disposable attributes, enabling access for a limited time or under specific usage conditions. This concept is particularly relevant in contexts where NFTs are used temporarily, such as in gaming, art, and culture, where they provide time-bound access to content or experiences​​.

### NFT Rentals

NFT Rentals allow individuals to access NFTs for a limited period without full ownership, using smart contracts as escrow. This method benefits both NFT owners, who can earn passive income by lending their NFTs, and renters, who can enjoy NFTs' privileges without the high ownership cost. There are two forms of NFT renting: collateral renting, where renters pay a fee and deposit collateral, and collateral-less renting, which does not require a deposit from the renter.

### P2P Loans

In the context of NFTs, Peer-to-Peer (P2P) loans allow NFT owners to use their digital assets as collateral for loans. This approach helps owners unlock liquidity from their NFT holdings without selling them. These loans typically involve creating a smart contract where the NFT is held as collateral until the loan is repaid. The specific terms, such as interest rates and repayment period, are agreed upon between the borrower and the lender. This system provides a unique opportunity for NFT owners to leverage the value of their digital assets while retaining ownership.

### Primary Sales Mint

"Primary Sales Mint" is often associated with NFTs' initial creation and sale. This process involves minting, creating, and recording a digital asset on the blockchain, making it an NFT. In primary sales, creators or project developers directly sell these NFTs to buyers. The minting process is crucial as it transforms a digital file into a unique, verifiable asset on the blockchain. Primary sales are significant for creators as they represent the first opportunity to monetize their digital artworks or assets directly to a community or the public.

### NFT Mandate

An NFT Mandate refers to mechanisms that commit to transferring NFTs at a later date, contingent on specific conditions or events. This concept is akin to a futures contract in traditional finance, where the ownership and transfer of an NFT are predetermined by a set of agreed-upon criteria in the future. These mandates are enforced through smart contracts, ensuring that the transfer of the NFT is executed automatically once the conditions are met. This method is beneficial when NFTs are used for event tickets, memberships, or other time-bound utilities.

### Post-Mint Utility

In NFTs, post-mint utility pertains to the added value and benefits introduced to an NFT collection after the initial minting process. This could include access to exclusive content, membership privileges, additional digital assets, or participation in community events. Enhancing NFTs with post-mint utility is a strategy.

***

## Gaming

### **P2E / Play to Earn**&#x20;

P2E is a game mechanic where players can earn cryptocurrency or digital assets actively participating in a game. This can include completing quests, winning battles, or achieving in-game objectives that result in tangible rewards. Players are incentivized to spend time and effort within the game to accumulate valuable assets.

### **P2O (Play to Own)**

P2O is a game mechanic that allows players to own in-game assets as actual digital property. These assets are typically represented as NFTs on the blockchain, providing players with full ownership rights. Players can freely buy, sell, and trade these assets, creating a player-driven virtual economy.

### **S2E (Swag to Earn)**&#x20;

Swag-to-Earn incentivizes players to earn from swagging. Players gain revenue from flaunting, showing off assets, attending fashion events, socializing with other players, and participating in virtual communities' entertainment activities. Metrics considered are as such: Social Index, Fashion Index, and Entertainment Index.

### **K2E (Kill-to-Earn)**

K2E is a game mechanic implemented in Battle Royale games where players are rewarded with cryptocurrency, digital assets, or in-game currency for eliminating other players (killing opponents) within the game. It introduces a competitive and lucrative element to traditional Battle Royale gameplay.

### **PEC (Play-Earn-Conserve)**

PEC is a model where players can engage with network-based games or web3 applications to earn economic incentives while actively contributing to nature conservation efforts. It combines gaming, blockchain, and environmental sustainability to create a rewarding and environmentally responsible gaming experience.

**Environmental Tokenomics:** PEC employs tokenomics that reward players with cryptocurrency or digital assets as they engage with eco-conscious games and applications. These incentives motivate users to participate and contribute to nature conservation initiatives.

**Proof of Conservation (PoC):** PoC is a consensus mechanism that verifies and rewards players for their contributions to environmental conservation. It may involve planting trees, reducing carbon footprint, or supporting eco-friendly projects.

### Metaverse / **Phygital**

"Metaverse" refers to a collective virtual shared space encompassing the digital and physical worlds, creating a persistent, immersive, and interconnected environment where users can interact, socialize, work, play, and design. The metaverse concept has gained significant attention in recent years, driven by technological advancements, augmented reality, virtual reality, blockchain, and the desire to create expansive digital universes.

#### **Phygital Metaverse**

The Phygital Metaverse is a fusion of the physical and digital worlds, where augmented reality (AR), virtual reality (VR), and blockchain technologies combine to create a seamless, immersive, and interconnected environment. It blurs physical and virtual reality boundaries, enabling users to interact with digital and real-world elements in a shared, persistent space. In the Phygital Metaverse, spatially-driven experiences, events, and exhibitions where users can simultaneously participate, explore, and engage with digital and physical elements are possible like never before.

#### **Digital Twins**&#x20;

Digital twins are digital representations or avatars of physical objects, spaces, or individuals. They enable synchronization between the physical and digital realms within the metaverse.

#### **Spatial Computing**

Spatial computing combines computer vision and augmented reality to enable real-time mapping of physical spaces, creating a foundation for interactions between physical and digital entities.

***

## **Project Categories**

### **Client-side Development**

Focuses on creating user-facing applications and interfaces that interact with blockchain technology for an improved user experience.

### **Smart Contracts**

It involves creating self-executing contracts with the terms directly written into code, enabling trustless and automated agreements on the blockchain.

### **Protocol Development**

Centers on developing and enhancing the underlying protocols and algorithms that form the backbone of blockchain networks, ensuring security, efficiency, and scalability.

### **Development Networks & Node Management**

Concerns the creation and maintenance of networks and nodes that support the blockchain infrastructure, ensuring robustness and reliability.

### **Tooling**

It involves developing tools and utilities that aid developers in building, testing, and deploying blockchain applications more efficiently.

### **Cryptographic Research and Development**

It focuses on advancing the security and efficiency of blockchain systems through innovative cryptographic techniques, including encryption, consensus algorithms, and privacy-preserving technologies.

***

## Grants & Funding

### Grantor

The entity providing financial or resource support for specific purposes, such as a foundation or DAO.

### Grantee

The recipient of financial or resource support awarded for specific purposes.

The criteria defining who can apply for a grant are often based on factors like project type, location, or organizational status.

### Grant Foundation

An organization provides financial support for specific purposes such as research, education, or social initiatives. It operates based on a mission that guides its funding decisions.

### Grant Committee

A group is responsible for reviewing grant applications, evaluating them against funding criteria, and deciding which projects receive financial support. It consists of experts relevant to the organization's focus areas.

### Award

The specific funds or resources granted to a successful applicant after proposal review and selection.

Request for proposal (RFP): advertisements outlining funding needs and criteria.

### Proposal

A document outlining the grantee's project, budget, objectives, and qualifications submitted for grant consideration.

### Evaluation

The process by which the grantor assesses the project's success.

### Funding Round

A specific period during which applications are accepted, and funds are distributed for a particular grant program.

### Matching Funds

Additional funding is secured by the grantee from other sources.

### In-Kind Contributions

Resources offered to support the project are valued as financial equivalents.

### Deliverables

Tangible outputs or outcomes expected from the grantee, outlined in the grant agreement and used to track project progress.

### Milestones

Key progress markers linked to deliverables and timelines, ensuring the project is on track and funds are used effectively.

### Impact Metrics / KPIs

Measurements of the lasting change your project makes beyond just finishing tasks.

### Quadratic Funding

A funding mechanism where contributions gain exponentially more significant impact with each additional donor, empowering smaller communities and diverse ideas.

***
