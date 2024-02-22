---
description: >-
  This document contains comprehensive information for project teams to know
  whether Avalanche is the right place to build with Granted.
cover: ../.gitbook/assets/docs hub header logo 1 (1).png
coverY: 0
---

# 🐎 Avalanche | $AVAX

## ⛰ Avalanche | $AVAX

Avalanche's open-source platform is designed to push the boundaries of blockchain technology, offering developers a powerful tool for building innovative and efficient applications. It features an energy-efficient consensus mechanism adaptable across various applications, making it ideal for global finance and sustainable blockchain projects. Key attributes include:

* **Versatility**: Supports a wide array of applications, facilitating easy development focusing on essential dApp components such as conflict resolution and transaction specifics.
* **EVM Compatibility**: Integrates the Ethereum Virtual Machine for backward compatibility with Ethereum's dApps and tools, enhancing throughput and reducing latency.
* **High Performance**: Processes thousands of transactions per second with a latency of just one to two seconds, ensuring efficiency and scalability for developers and validators.

## ⌚️ Background

Avalanche was developed by [Emin Gün Sirer](https://cointelegraph.com/top-people-in-crypto-and-blockchain-2022/emin-gun-sirer) and his team from Cornell University to surpass existing blockchain limitations, focusing on high throughput, scalability, and security without sacrificing decentralization. Launched in 2020, Avalanche marked a significant milestone in blockchain technology, promising to outperform Ethereum with its innovative consensus mechanism that blends the best aspects of Nakamoto consensus (used in Bitcoin) with classical consensus mechanisms. The platform's ability to process thousands of transactions per second with latencies as low as one to two seconds showcased its potential to support various applications, from decentralized finance (DeFi) to complex enterprise solutions​​​​​​.

Avalanche's native token, AVAX, plays a crucial role in the ecosystem, facilitating transactions and paying for fees, and serving as a reward mechanism for validators who secure the network. The platform's economic model balances inflation from new token issuance with deflationary pressures from token burns, aiming to create a sustainable ecosystem that rewards participation and usage. Since its launch, Avalanche has attracted significant interest and investment, including a [$230 million funding round](https://medium.com/avalancheavax/polychain-capital-three-arrows-capital-lead-230m-investment-in-avalanche-ecosystem-1f0622fdf03a) in 2021 from prominent investors like Polychain and Three Arrows Capital.

{% embed url="https://www.coingecko.com/en/coins/avalanche" %}

## 🗺️ Ecosystem

Avalanche's ecosystem is already making significant real-world impacts across various sectors, demonstrating the versatility and effectiveness of its fast, flexible blockchain technology. Here are several prime examples highlighting its current applications:

1. [**Insurance with Lemonade**](https://www.lemonade.com/): In Kenya, Lemonade leverages Avalanche to provide crop insurance to small farmers through an app. This solution offers automatic payouts in response to damaging weather conditions, utilizing smart contracts and oracles for an efficient, automated process​​​​​​.
2. [**Disaster Relief by Deloitte**](https://www2.deloitte.com/us/en.html): Avalanche streamlines the management of FEMA Public Assistance payments, enhancing automation, security, and transparency in the disaster relief process. This application proves crucial as natural disasters become more frequent due to climate change​​​​​​.
3. [**Ticketing with Dreamus**](https://www.dreamuscompany.com/): Dreamus's ticketing app in South Korea offers a transparent, counterfeit-proof system. This technology addresses issues like scalping and secondary market abuses, benefiting users and the industry​​​​​​.
4. [**Structured Finance via Intain**](https://intainft.com/): Intain creates a marketplace for tokenized assets. This platform enhances transparency, liquidity, and efficiency in the structured finance market, catering to asset lenders and investors​​​​​​.
5. [**Gaming Innovation with Gunzilla**](https://medium.com/avalancheavax/gunzilla-launches-aaa-shooter-on-an-avalanche-subnet-27d29c6eb593): The Gunzilla platform, developed on an Avalanche Subnet, is designed for gamers and blockchain enthusiasts, introducing a Play-to-Own model in its AAA battle royale game  "[Off the Grid](https://gameoffthegrid.com/)." This integration of blockchain technology aims to enhance the gaming experience by offering unique rewards and digital ownership.
6. [**E-commerce and Loyalty with Tyb/Shopify**](https://www.avax.network/blog/tyb-and-shopify-bring-web3-loyalty-platform-to-major-consumer-brands-powered-by-avalanche): TYB leverages Avalanche to offer a community-powered loyalty solution for Shopify merchants. This integration enables innovative rewards through digital collectibles, enhancing brand and fan engagement​​​​​​.
7. [**Supply Chain / Certification by Blockticity**](https://www.avax.network/blog/blockticity-mints-275m-in-hemp-and-other-product-certifications-on-avalanche): To combat fraud in the supply chain, Blockticity uses Avalanche to mint certifications for products. By linking certifications to an Avalanche NFT via a QR code, consumers and vendors can verify authenticity, with applications ranging from hemp and cannabis to potentially sneakers and fruit​​​​​​.

## 🪙 Grant Program

Granted has partnered with Avalanche to provide Grant opportunities to builders, infrastructure providers, researchers, and application developers. Avalanche is looking to provide grants to projects in the following spaces:&#x20;

* **(...) TO BE DETERMINED (...)**.

Granted and Avalanche strongly encourages all projects contributing to the growth of the Aleph Zero ecosystem to share their projects with us, especially those that fit under any categories known to be prioritized by the community.&#x20;

🪧 [Apply Here! ](https://www.getgranted.io/granted-application)

## 🧱 Tech Stack

### Avalanche Primary Network/Mainnet

Avalanche's Primary Network is a diverse ecosystem comprising three separate blockchains, coming together to form the Avalanche Mainnet, which includes the Primary Network and all deployed subnets. The Primary Network consists of three leading chains:

1. **Contract Chain (C-Chain)**: Implements the Ethereum Virtual Machine (EVM), allowing for the deployment and execution of smart contracts written in Solidity. It is designed to be compatible with Ethereum's development tools and practices.
2. **Platform Chain (P-Chain)**: Manages validator and subnet operations, including creating new blockchains and subnets, adding validators to subnets, and conducting staking operations. It acts as the backbone of the network's structure and validator coordination.
3. **Exchange Chain (X-Chain)**: Handles digital smart assets known as Avalanche Native Tokens, which can represent real-world resources with specific rules. This chain supports creating and exchanging these tokens, with AVAX being the primary asset for transaction fees.

### Consensus Mechanism

The Avalanche Consensus mechanism is a state-of-the-art blockchain network protocol focusing on scalability, durability, and decentralization. It integrates the best aspects of classical and Nakamoto consensus mechanisms, ensuring swift, secure consensus among nodes. Key elements of the Avalanche Consensus include:

* **Mechanism**: Utilizes sub-sampled voting, where nodes consult a random subset of validators to decide on transaction validity. This method ensures rapid and efficient consensus, with safeguards to exclude invalid transactions, like those exceeding the account's AVAX balance.
* **Consensus Achievement**: Defined by two adjustable parameters: "α" (alpha) for the required majority and "β" (beta) for the confidence threshold or consecutive rounds needed. This flexibility allows for quick finalization of transactions without conflicts, enhancing network throughput and reliability.
* **Conflict Resolution**: In transaction conflicts, the system enables validators to converge towards a consensus decisively, ensuring only non-conflicting transactions are accepted. This process prevents bottlenecks and maintains the integrity and smooth functioning of the network.

### Avalanche Virtual Machine

AWM is likely a feature designed to facilitate communication within the Avalanche ecosystem, possibly enabling secure message passing between wallets or smart contracts. For detailed information, searching for "Avalanche Wallet Messaging" or "AWM Avalanche" on the official Avalanche documentation site or developer forums can yield specific insights into its functionalities, use cases, and integration guides.

### **Avalanche Warp Messaging**

Avalanche Warp Messaging (AWM) allows Virtual Machine (VM) developers to implement arbitrary communication protocols between any two Avalanche Subnets, providing native cross-subnet communication for dApps and developers in the ecosystem. The common use-cases for this configuration include deploying cost-efficient Oracle Networks, execution of token transfers, and state sharding between Subnets.

### **Avalanche Teleporter**

The Avalanche Teleporter is a sophisticated messaging protocol designed to enhance cross-chain communication within the Avalanche ecosystem. Built upon Avalanche Warp Messaging (AWM), Teleporter offers developers a streamlined interface for both sending and receiving messages across different EVM instances, and introduces several advanced features, such as replay protection, retry capabilities for message delivery, relay incentivization, and the specification of allowed relayers, enhancing the reliability and functionality of cross-chain interactions.

**Avalanche HyperVM (HyperVM)**

HyperVM is possibly a new or enhanced virtual machine designed for executing smart contracts on the Avalanche platform, offering improvements in speed, efficiency, or developer capabilities over existing VM solutions. For comprehensive information, consider looking up "Avalanche HyperVM" or "HyperVM Avalanche" on the official Avalanche developer resources, tech blogs, and community discussions for deep dives into its architecture, features, and development tutorials.

### Avalanche HyperSDK

The Avalanche HyperSDK is a powerful toolset designed to empower developers to easily create custom virtual machines (VMs) on the Avalanche platform, facilitating the development of specialized blockchains. This innovative SDK streamlines the process of leveraging Avalanche's capabilities to build blockchains that are tailored to specific use cases, ensuring they are both high-performing and adaptable to future needs.

## 🛣️ Roadmap

Avalanche's development roadmap focuses on continuously improving its infrastructure to support a growing number of applications and users. By enhancing scalability, security, and user experience, Avalanche aims to maintain its position at the forefront of blockchain innovation. Ongoing updates and partnerships, including significant collaborations with industry giants like Amazon, reflect Avalanche's commitment to expanding its ecosystem and increasing adoption across various sectors.

For the 2024 roadmap, Avalanche plans a series of strategic and technical upgrades to enhance the platform's efficiency, scalability, and user experience. The significant areas of focus are as follows:

1. **Base Layer Consensus Improvements**: Target to cut down the time to finality to below 250 milliseconds, introducing an "optimistic fast finality" mode potentially within one or two rounds. Integrating these upgrades across all APIs will aim to offer users near-instantaneous interactions.
2. **Consensus Capacity Upgrades**: Suggest transitioning the c-chain to a non-primary subnet, necessitating enhanced hardware capabilities. Building on Avalanche's inherent efficiency, this move is expected to boost network and storage capacity significantly.
3. **Deep Code Refactoring**: Plan to substantially reduce technical debt by eliminating most Geth code, retaining only essential state transition logic. This step should minimize Geth dependency, facilitating quicker and safer VM and code updates.
4. **Database Upgrades**: Propose the adoption of FirewoodDB, a linear-access database optimized for blockchain data, after the code overhaul. This should improve the EVM's (and other VMs') read-write efficiency, addressing the substantial processing time currently spent on state data access.
5. **Subnet Upgrades**: To support c-chain-native elastic subnet staking, expanding beyond the current limitation to tokens on the x/p-chains. This capability is crucial given that most active tokens reside on the c-chain, marking a significant advancement for the ecosystem.
6. **AWM and Teleporter Development**: Aim to advance Avalanche Wallet Messaging (AWM) and Teleporter to total production, achieving sub-second time-to-finality for messages between subnets. This would position Avalanche as having the fastest chain-to-chain state transitions in the industry.
7. **HyperSDK Enhancement**: Improve HyperSDK to enable simple modifications and upgrades across chain components, promoting rapid experimentation. This toolkit is envisioned as a comprehensive solution for easy chain component adjustments.
8. **New VMs Introduction**: Advocate for adopting HyperVM, Avalanche's advanced native VM, capable of optimizations beyond the current c-chain's reach, potentially revolutionizing the platform's performance and capabilities.

## 🎭 Community

The Avalanche community is a vibrant ecosystem of developers, entrepreneurs, and enthusiasts committed to exploring the potential of decentralized technology. With an emphasis on collaboration and open-source development, the community plays a crucial role in driving the platform's evolution. Engagement opportunities, including governance participation, staking, and educational resources, empower individuals to contribute to the network's growth and security.

For more information and to engage with the Avalanche community, you can visit the following resources:

* Website: [https://avax.network](https://avax.network/)
* Social Media: [X](https://twitter.com/avax), [Discord](https://chat.avalabs.org/), [Github](https://github.com/ava-labs), [LinkedIn](https://linkedin.com/company/avalancheavax), [Reddit](https://www.reddit.com/r/avax)
* Forum: [https://forum.avax.network/](https://forum.avax.network/)

## 📚 Resources

For those interested in diving deeper into Avalanche, a wealth of resources is available:

* Documentation: [https://docs.avax.network](https://docs.avax.network/)
* Whitepapers: [https://www.avalabs.org/whitepapers](https://www.avalabs.org/whitepapers)&#x20;
* Additional articles:&#x20;
  * Overview of Avalanche Consensus ([Avax Docs](https://docs.avax.network/learn/avalanche/avalanche-consensus))
  * The Avalanche Ecosystem ([Coindesk](https://coinmarketcap.com/academy/article/what-is-avalanche-a-guide-to-avalanche-s-ecosystem), [Avax Blog](https://www.avax.network/blog/7-avalanche-use-cases)).
  * Avax 2024 Roadmap ([Tweet by Kevin Sekniqi](https://twitter.com/kevinsekniqi/status/1741234199250731484)).
  * Introducing the Avalanche HyperSDK ([Avax Blog](https://www.avax.network/blog/introducing-hypersdk-a-foundation-for-the-fastest-blockchains-of-the-future))
  * Avax Teleporter Protocol ([Avax Docs](https://docs.avax.network/build/cross-chain/teleporter/overview))
  * Avalanche Warp Messaging Protocol ([Avax Docs](https://docs.avax.network/build/cross-chain/awm/overview))
