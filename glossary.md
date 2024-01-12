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

# 🔖 Glossary

## Blockchain

### **Layer 1 (L1)**

Layer 1 blockchains are the foundational networks of the blockchain world. They operate independently and can validate and finalize transactions on their own, without needing another network's assistance. Popular examples of L1 blockchains include Bitcoin, Ethereum, and Binance Smart Chain. To improve scalability and transaction speed, L1 solutions might involve modifying the blockchain's rules or protocols. This can include consensus protocol improvements (such as transitioning from Proof of Work to Proof of Stake) or implementing sharding, where the blockchain is divided into smaller, more manageable parts that can process data in parallel​​​​.

### **Layer 2 (L2)**&#x20;

Layer 2 solutions are built on top of Layer 1 blockchains and are designed to enhance scalability and efficiency. They achieve this by handling a portion of the transactional workload off the main chain, thereby reducing congestion. L2 solutions include rollups, state channels, and nested blockchains. Rollups bundle multiple transactions and validate them before submitting them as a single transaction to the main chain. State channels allow two-way communication for transactions off the main chain. Nested blockchains involve secondary chains working under the main chain's rules, handling day-to-day transactions and reporting back to the main chain only for finalization or dispute resolution. Examples of Layer 2 solutions are the Bitcoin Lightning Network, Ethereum's Raiden, and platforms like Optimism and Arbitrum, which use rollup technology​​​​.

### **Layer 3 (L3)**

Layer 3 focuses on interoperability between different blockchain networks and is designed to further enhance the scalability of blockchain networks beyond the capabilities of L1 and L2. It offers an infrastructure for the development of more complex decentralized applications (dApps) that require advanced features and functionalities.

### **Layer 4 (L4)**

Layer 4 is where most decentralized applications (dApps) run, using smart contracts to execute their business logic​, and is often referred to as the application or user interface layer in the blockchain architecture. It represents the entry point for users into the blockchain ecosystem, providing user-friendly interfaces and interactions with the underlying blockchain technology.

### **Sidechains**

Sidechains are independent blockchain networks that link to a parent blockchain (like Bitcoin or Ethereum) through a two-way peg. They have their own consensus protocols and can operate independently, improving privacy and security. The key feature of sidechains is their ability to facilitate the transfer of digital assets between the mainnet and the sidechain, allowing users to move assets across networks seamlessly. They essentially expand the capabilities of the main blockchain by allowing more experimental or niche applications without overburdening the main network​​, while still being linked to the network's ecosystem and security.

### **Yield Farming**

Users can stake their on-chain assets such as tokens or in-game assets (NFTs) to earn additional rewards.

### **Decentralized Autonomous Organizations (DAOs)**

Users collectively govern network/application roadmap decisions and management assets through community governance.

***

## NFTs

### **ERC-721 NFTs**

ERC-721 is a standard for NFTs on the Ethereum blockchain. Each ERC-721 token is unique and cannot be exchanged on a one-to-one basis with other tokens. These NFTs are often used to represent ownership of digital or physical assets, such as artwork, collectibles, virtual real estate, and more.

### **ERC-1155 NFTs**

ERC-1155 is another standard for NFTs on the Ethereum blockchain, designed to be more flexible than ERC-721. ERC-1155 tokens can represent both fungible and non-fungible assets within a single contract. This means that a single ERC-1155 contract can handle multiple types of NFTs, offering greater efficiency and versatility for developers.

**Key Differences:**

* **Uniqueness vs. Multi-Fungibility:** ERC-721 tokens are unique and non-fungible, meaning each token has distinct properties or attributes. ERC-1155 tokens can be both non-fungible and fungible within the same contract, allowing developers to create various token types in a single deployment.
* &#x20;**Efficiency and Gas Costs:** ERC-1155 is often considered more gas-efficient than ERC-721, as it allows for the management of multiple token types in a single contract. This can result in cost savings for developers and users when interacting with these tokens on the Ethereum blockchain.
* **Interoperability** ERC-721 tokens are widely supported by NFT marketplaces, wallets, and applications due to their standardization and popularity. While ERC-1155 tokens offer more flexibility in terms of creating custom token types, but adoption may vary across platforms.

**Metadata and Attributes:** Both ERC-721 and ERC-1155 tokens can include metadata and attributes to provide additional information about the assets they represent. This information is often used for display and interaction purposes in NFT applications.

**Smart Contract Complexity:** ERC-721 contracts tend to be simpler, as they deal with individual unique tokens. ERC-1155 contracts can be more complex due to the handling of multiple token types, but they offer a single contract solution for managing diverse assets.

**Batch Operations:** ERC-1155 allows batch operations, making it more efficient for performing actions on multiple tokens at once, which can be especially useful in gaming scenarios.

### **ERC-998 Composable NFTs**

ERC-998 is an extension of ERC-721 that enables the creation of composable NFTs. These NFTs can hold other NFTs or fungible tokens, creating nested ownership structures. It's often used for complex in-game items and assets in blockchain-based games.

### **ERC-20 and NFT Bridges**

Some projects have developed bridges or standards to convert ERC-20 tokens (fungible tokens) into NFTs and vice versa. This innovation allows for unique fungible tokens or fractional ownership of NFTs.

### **Fractional Ownership**

Fractional ownership is achieved by dividing an NFT into smaller, tradable units, often represented as fungible tokens on a blockchain. These fungible tokens, sometimes called "NFT shares" or "NFT fractions," can be bought, sold, and traded like regular tokens.&#x20;

**Benefits of Fractional Ownership:**

* **Access to High-Value NFTs:** Fractional ownership democratizes access to high-value NFTs that may be out of reach for individual buyers. Investors can pool their resources to collectively own prestigious NFTs.
* **Liquidity and Trading:** Fractional ownership tokens can be freely traded on secondary markets, providing liquidity to NFT investors. This allows token holders to exit their investment or trade their shares more easily.
* **Collective Decision-Making:** Token holders often participate in governance decisions regarding the NFT. This can include voting on whether to sell the NFT, display it in a virtual gallery, or use it in a decentralized application (dApp).
* **Reduced Risk:** Fractional ownership can mitigate the risk associated with investing in a single NFT. If the NFT's value fluctuates, the impact on each token holder is proportionate to their ownership share.

**Use Cases and Applications:**

* **Art Ownership:** Fractional ownership allows multiple art enthusiasts to collectively own valuable digital artworks, granting them the right to display the artwork in their virtual galleries or sell their shares.
* **Real Estate and Virtual Land:** In virtual worlds and metaverse platforms, fractional ownership can apply to virtual real estate or land parcels, enabling shared ownership of virtual properties.
* **Music Royalties:** Musicians and creators can tokenize ownership of their music rights and distribute them among investors, allowing for shared revenue from music sales and royalties.
* **Collectibles and Rare Items:** High-value collectibles and rare in-game items can be fractionalized, making them more accessible to a wider audience of collectors and gamers.

It's important to note that the implementation of fractional ownership may vary depending on the blockchain platform and the specific smart contract used. Additionally, regulatory considerations may apply, so participants should be aware of legal requirements and tax implications related to fractional ownership of NFTs in their respective jurisdictions.

### Stateful NFTs

Stateful NFTs, also known as "Smart NFTs" or "Interactive NFTs," are a type of non-fungible token (NFT) that goes beyond static digital assets. Unlike traditional NFTs, which primarily represent ownership of a unique item or piece of content, stateful NFTs can change, adapt, or respond to various inputs, conditions, or interactions. Here are key characteristics and examples of stateful NFTs:

**Characteristics of Stateful NFTs:**

1. **Programmability:** Stateful NFTs are programmable and contain embedded code or smart contracts that enable them to perform specific actions or respond to triggers.
2. **Interactivity:** These NFTs can interact with external data sources, user inputs, or other smart contracts, allowing them to change their behavior or appearance in real-time.
3. **Dynamic Attributes:** Stateful NFTs can have dynamic attributes or properties that can be modified or updated over time. These attributes can affect the NFT's appearance, functionality, or value.
4. **Utility and Functionality:** Stateful NFTs often have utility or functionality beyond simple ownership. They can represent access rights, memberships, or in-game items that can be used in decentralized applications (dApps) or virtual worlds.

**Examples of Stateful NFTs:**

1. **Virtual Pets:** Stateful NFTs can represent virtual pets or creatures that require care and interaction. Owners may need to feed, play with, or train their virtual pets to make them grow or gain new abilities.
2. **In-Game Items:** In blockchain-based games, stateful NFTs can be in-game items that have attributes, abilities, and durability. For example, a sword NFT could level up and become more powerful through use in the game.
3. **Art and Music NFTs:** Interactive art or music NFTs can change their appearance or play different compositions based on external factors like time of day, weather conditions, or user interactions.
4. **Collectible Cards:** Stateful NFTs can represent collectible cards that evolve or gain new abilities over time, creating dynamic gameplay experiences in blockchain card games.
5. **Virtual Real Estate:** Virtual land NFTs can have stateful features, such as the ability to build structures or generate resources over time. Owners can develop their virtual properties within decentralized metaverse platforms.
6. **Membership and Access Tokens:** Stateful NFTs can serve as membership or access tokens to exclusive communities, events, or content. Ownership of these NFTs grants privileges and access to specific areas or features within a platform or ecosystem.
7. **Dynamic Art and Stories:** Interactive artworks or narratives can change based on user interactions or external data, offering unique storytelling experiences through NFTs.
8. **Utility Tokens:** Some NFTs act as utility tokens within dApps or platforms, enabling specific actions or functions, such as voting, governance participation, or resource allocation.

### Soulbound Tokens (SBT)

Soulbound Tokens (SBTs) are an emerging concept within the Web3 ecosystem, focusing on creating a more identity-centric and decentralized society.&#x20;

1. **Definition and Origin**: SBTs are non-transferable, non-financialized digital tokens introduced by Ethereum creator Vitalik Buterin, along with economist E. Glen Weyl and lawyer Puja Ohlhaver. They are meant to represent a person's identity, reputation, and affiliations within a decentralized society (DeSoc)​​​​.
2. **Primary Features and Use Cases**: SBTs are unique because they cannot be transferred or sold. They are designed to hold and represent a person's credentials and achievements within the Web3 space. SBTs have a variety of potential applications, such as enhancing trust among community members, governance rights and delegated authority in DAOs, KYC requirements, credit scoring, combating bots and spam on social media platforms, e-government voting, and achievement-based items in Web3 games​​​​.
3. **Potential Impact on Society**: SBTs are proposed as foundational elements for a DeSoc, which focuses on social identity and community-driven initiatives rather than just financial transactions. They could play a significant role in merging physical and virtual worlds, such as in the metaverse, by representing human relationships and social constructs​​.
4. **Pros and Cons**: While SBTs offer the potential for more democratic governance structures and could facilitate trust and verification processes, they also raise concerns. These include the challenges in recovering lost "Souls" (wallets that hold SBTs), the risk of turning into a social credit system, and the ethical implications of a reputation-based society​​​​.
5. **Development Stage**: As of now, SBTs are still a nascent concept, with various aspects needing further exploration and development. The idea is gaining traction, and its proponents believe it could significantly shape the future of Web3 and decentralized societies​​.

In conclusion, Soulbound Tokens represent an intriguing development in the Web3 space, aiming to blend decentralized technology with social identity and community structures. However, as with any emerging technology, there are challenges and ethical considerations that need to be addressed as the concept evolves.

### **NFT Drops**

Exclusive Non-Fungible Token (NFT) assets that are distributed to users/players as rewards.

### **NFT Marketplaces**

Integration with NFT marketplaces like OpenSea or Rarible for trading on-chain assets.

***

## Gaming

### **P2E / Play to Earn**&#x20;

P2E is a game mechanic where players can earn cryptocurrency or digital assets by actively participating in a game. This can include completing quests, winning battles, or achieving in-game objectives that result in tangible rewards. Players are incentivized to spend time and effort within the game to accumulate valuable assets.

### **P2O (Play to Own)**

P2O is a game mechanic that allows players to own in-game assets as true digital property. These assets are typically represented as NFTs on the blockchain, providing players with full ownership rights. Players can buy, sell, and trade these assets freely, creating a player-driven virtual economy.

### **S2E (Swag to Earn)**&#x20;

Swag-to-Earn incentivizes players to earn from swagging. Players gain revenue from flaunting, showing off assets, attending fashion events, socializing with other players and involving in entertainment activities in virtual communities. Metrics considered are as such: Social Index, Fashion Index and Entertainment Index.

### **K2E (Kill-to-Earn)**

K2E is a game mechanic implemented in Battle Royale games where players are rewarded with cryptocurrency, digital assets, or in-game currency for eliminating other players (killing opponents) within the game. It introduces a competitive and lucrative element to traditional Battle Royale gameplay.

### **PEC (Play-Earn-Conserve)**

PEC is a model where players can engage with network-based games or other web3 applications to earn economic incentives while actively contributing to nature conservation efforts. It combines gaming, blockchain, and environmental sustainability to create a rewarding and environmentally responsible gaming experience.

**Environmental Tokenomics:** PEC employs tokenomics that reward players with cryptocurrency or digital assets as they engage with eco-conscious games and applications. These incentives motivate users to participate and contribute to nature conservation initiatives.

**Proof of Conservation (PoC):** PoC is a consensus mechanism that verifies and rewards players for their contributions to environmental conservation. It may involve actions such as planting trees, reducing carbon footprint, or supporting eco-friendly projects.

### Metaverse / **Phygital**

"Metaverse" refers to a collective virtual shared space that encompasses the digital and physical worlds, creating a persistent, immersive, and interconnected environment where users can interact, socialize, work, play, and create. The concept of the metaverse has gained significant attention in recent years, driven by advancements in technology, augmented reality, virtual reality, blockchain, and the desire to create expansive digital universes.

#### **Phygital Metaverse**

The Phygital Metaverse is a fusion of the physical and digital worlds, where augmented reality (AR), virtual reality (VR), and blockchain technologies combine to create a seamless, immersive, and interconnected environment. It blurs the boundaries between physical and virtual reality, enabling users to interact with both digital and real-world elements in a shared, persistent space. In the Phygital Metaverse, spatially-driven experiences, events, and exhibitions, where users can participate, explore, and engage with digital and physical elements simultaneously are possible, like never before.

#### **Digital Twins**&#x20;

Digital twins are digital representations or avatars of physical objects, spaces, or even individuals. They enable synchronization between the physical and digital realms within the metaverse.

#### **Spatial Computing**

Spatial computing combines computer vision and augmented reality to enable real-time mapping of physical spaces, creating a foundation for interactions between physical and digital entities.

***

## **Project Categories**

**Client-side Development:** Focuses on creating user-facing applications and interfaces that interact with blockchain technology for an improved user experience.

**Smart Contracts:** Involves creating self-executing contracts with the terms directly written into code, enabling trustless and automated agreements on the blockchain.

**Protocol Development:** Centers on developing and enhancing the underlying protocols and algorithms that form the backbone of blockchain networks, ensuring security, efficiency, and scalability.

**Development Networks & Node Management:** Concerns the creation and maintenance of networks and nodes that support the blockchain infrastructure, ensuring robustness and reliability.

**Tooling:** Involves developing tools and utilities that aid developers in building, testing, and deploying blockchain applications more efficiently.

**Cryptographic Research and Development:** Focuses on advancing the security and efficiency of blockchain systems through innovative cryptographic techniques, including encryption, consensus algorithms, and privacy-preserving technologies.
