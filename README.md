# NFT Ticketing Platform

## Problems to be Solved

1. **Fraud and Counterfeiting**  
   Fake tickets are a common issue, leading to fans being turned away at events and damaging the artist's reputation.
   
2. **Scalping and Reselling**  
   Scalpers buy large quantities of tickets and resell them at inflated prices, making it difficult for genuine fans to access affordable tickets.
   
3. **Platform Fees**  
   Ticketing platforms often charge high service fees, increasing the cost for fans and reducing the artist’s revenue share.
   
4. **Bots and Automation**  
   Automated bots purchase tickets in bulk as soon as they go on sale, leaving little chance for human fans to buy them.

## Key Features (Some under development)

1. **Scalping and Reselling Control**  
   - NFT-based tickets can use smart contracts to prevent or control scalping.
   - Artists can set resale price limits or receive royalties from resales.

2. **Fraud Prevention**  
   - NFTs are unique and verifiable on the blockchain, making counterfeit tickets nearly impossible.
   
3. **Lower Platform Fees**  
   - Decentralized platforms can bypass traditional high-fee ticketing systems, benefiting both artists and fans.

4. **Bot and Automation Mitigation**  
   - Smart contracts can limit the number of tickets an individual can purchase, reducing the impact of bots.

### Additional Features

- **Dynamic Pricing Models**  
   Adjust ticket prices in real-time based on demand.
   
- **Fan Engagement & Rewards**  
   NFTs can offer exclusive content, backstage passes, or other perks, fostering fan loyalty.

- **Streamlined Event Access**  
   Digital verification for faster event entry.

## Platform Features

- **Homepage**:  
  Separate login options for artists and customers.
  
- **Web3 Ticketing**:  
  NFT tickets serve as both collectibles and certificates of entry.

- **Web3 Community Building**:  
  Community Tokens for memberships and exclusive experiences.

- **Collectibles**:  
  NFTs can be tied to albums, artwork, or physical items and traded on secondary marketplaces.

- **Limited Editions & Tiers**:  
  Offers varied perks for different ticket tiers.

- **Exclusive Access & Token Gating**:  
  Allows exclusive access to ticket sales or events for token holders.

- **Push Notifications & Airdrops**:  
  Direct communication with fans via the platform wallet.

- **Promo Codes**:  
  Offers unique discounts or special access through promo codes.

- **Physical Redeemables & Associated Media**:  
  NFTs can be tied to physical merchandise or include audio/video content.

---
## Important Note

- **Not all features mentioned are currently implemented**. Some are in progress, while others are planned for future updates.
- 
## Technology Stack & Tools

- **Solidity** – Writing Smart Contracts & Tests
- **JavaScript** – React & Testing
- **Hardhat** – Development Framework
- **Ethers.js** – Blockchain Interaction
- **React.js** – Frontend Framework
- **MetaMask** – Blockchain Wallet Integration

---

## Requirements for Initial Setup

1. Install [NodeJS](https://nodejs.org/en/) (LTS version recommended).
2. Install [MetaMask](https://metamask.io/) on your browser.

---

## Setting Up

### 1. Clone/Download the Repository

```bash
$ git clone <repo-link>
```

### 2. Install Dependencies

```bash
$ npm install
```

### 3. Run Tests

```bash
$ npx hardhat test
```

### 4. Start Hardhat Node

```bash
$ npx hardhat node
```

### 5. Run Deployment Script

In a separate terminal, execute:

```bash
$ npx hardhat run ./scripts/deploy.js --network localhost
```

### 6. Start Frontend

```bash
$ npm run start
```

---

