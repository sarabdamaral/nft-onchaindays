# NFT Smart Contract Project

This project demonstrates a basic NFT (Non-Fungible Token) implementation using OpenZeppelin's ERC721 standard.

## Prerequisites

- Git
- Node.js (installed via nvm)

## Installation

### 1. Install NVM (Node Version Manager)

#### On macOS/Linux:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```

#### On Windows:
Download and install NVM for Windows from: https://github.com/coreybutler/nvm-windows/releases

### 2. Install Node.js using NVM
```bash
# Install the latest LTS version of Node.js
nvm install --lts

# Use the installed version
nvm use --lts
```

### 3. Clone the repository and install dependencies
```bash
# Clone the repository (if you haven't already)
git clone <your-repo-url>
cd my-nft

# Install project dependencies
npm install
```

### 4. Configure Environment Variables

1. Copy the example environment file:
```bash
cp .env.example .env
```

2. Open the `.env` file and fill in your values

## Usage

### 1. Compile the contract

```bash
npx hardhat compile
```

### 2. Deploy the NFT contract

```bash
node scripts/deploy.js
```

### 3. Save the metadata to IPFS (using Pinata for example)

### 4. Mint an NFT

```bash
node scripts/mint-nft.js
```