# Agent Pods  

---

## 📖 Description

AgentPods is a decentralized platform for creating and monetizing **Intelligent NFTs (iNFTs)** that encapsulate AI agents or models.  
Users can **mint**, **lease** and **run AI inference jobs** on-chain while model storage, execution and availability are handled via the **0G ecosystem**.  

This enables **secure ownership**, **transparent monetization** and **censorship-resistant AI services** that are verifiable on-chain.

---

## 📚 Table of Contents

1. [Description](#-description)  
2. [Getting Started](#-getting-started)  
   - [Prerequisites](#prerequisites)  
3. [Usage](#-usage)  
4. [Key Features](#-key-features)  
5. [Unique Selling Point](#-unique-selling-point)  
6. [Tech Stack Used](#-tech-stack-used)  

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** v18 or higher  
- **npm** or **pnpm** package manager  
- A **0G Galileo Testnet wallet** with test tokens  
- **Git** installed  
- **Basic Web3 wallet** (MetaMask recommended)

---

## 🛠 Usage

1. **Mint an AI Agent iNFT** – Upload your AI model to **0G Storage** and store the reference in the NFT metadata.  
2. **List for Lease** – Allow others to rent and run your AI agent for a fee.  
3. **Run Inference Jobs** – Renter submits an input, job runs on **0G Compute** and output is stored in **0G Storage** or **0G DA**.  
4. **Settle Payments** – Lease smart contract handles usage receipts and payment settlement.  
5. **Verify & View** – All activity is transparent on the 0G Chain and viewable via explorer.

---

## 🔑 Key Features

- **On-chain AI Ownership** – Securely own AI models as iNFTs.  
- **AI Leasing Marketplace** – Monetize models via time based or usage based leasing.  
- **Verifiable Compute** – Jobs executed via 0G Compute are recorded and traceable.  
- **Decentralized Storage** – Models, datasets and outputs stored on 0G Storage.  
- **EVM Compatible** – Built on 0G Chain with Solidity smart contracts.

---

##  Why This Project is Required & Problems It Solves ?

AI in Web3 today faces 4 major challenges:

1. **Centralized Model Hosting** – Most AI models are stored and served by centralized providers, creating dependency, censorship risk and single points of failure.
2. **Lack of True Ownership** – NFTs usually store static images or metadata not functional AI agents that users can actually own, run or improve.
3. **Opaque Computation** – AI outputs from centralized APIs are unverifiable, making it impossible to confirm whether the claimed model was actually used.
4. **No Monetization Path for AI Creators** – Independent AI developers have no simple, trustless way to monetize models while retaining full control.

**AgentPods** solves these issues by:

- Turning AI models into **on-chain Intelligent NFTs (iNFTs)** with verifiable storage and execution.
- Using **0G Storage** for censorship-resistant hosting of models, configs and datasets.
- Running inference jobs on **0G Compute** and recording proofs in **0G Data Availability (DA)** for auditability.
- Enabling **permissionless leasing and monetization** through smart contracts on **0G Chain**.

This ensures AI agents are **ownable, rentable, verifiable and censorship resistant** -> a core need for truly decentralized AI ecosystems.

---

## USP

Unlike centralized AI platforms, AgentPods provides **true digital ownership** of AI models, **on-chain verifiable computation** and a **permissionless AI marketplace**. This enables AI creators to monetize without intermediaries, while users get provably fair access to AI services.

---

## Tech Stack Used :

- **0G Chain** – EVM compatible blockchain for contracts & transactions  
- **0G Storage** – Decentralized large file and model storage  
- **0G Compute** – Distributed compute network for AI inference  
- **0G Data Availability (DA)** – Scalable storage for high throughput AI output logs  
- **Solidity** – Smart contract development  
- **Hardhat** – Contract compilation & deployment  
- **Next.js** – Web frontend  
- **Wagmi + Ethers.js** – Blockchain interaction from frontend  
