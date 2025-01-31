
# Solana NFT Project

This repository contains a Solana-based NFT (Non-Fungible Token) project. It provides the necessary tools and scripts to create, mint, and manage NFTs on the Solana blockchain.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is designed to help developers and creators easily mint and manage NFTs on the Solana blockchain. It includes scripts for creating metadata, deploying NFTs, and interacting with the Solana network.

## Features
- Mint NFTs on the Solana blockchain.
- Generate metadata for NFTs.
- Deploy NFTs to the Solana devnet or mainnet.
- Easy-to-use scripts for managing NFTs.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/comdev99/solanaNFT.git
   cd solanaNFT
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

3. Set up your Solana CLI:
   ```bash
   solana config set --url devnet
   solana-keygen new
   ```

## Usage
### Minting NFTs
To mint an NFT, run the following command:
```bash
yarn mint-nft
# or
npm run mint-nft
```

### Generating Metadata
To generate metadata for your NFT, use the following script:
```bash
yarn generate-metadata
# or
npm run generate-metadata
```

### Deploying NFTs
To deploy your NFT to the Solana network:
```bash
yarn deploy-nft
# or
npm run deploy-nft
```

## Configuration
You can configure the project by editing the `config.json` file. This file includes settings for the Solana network, NFT metadata, and other parameters.

Example `config.json`:
```json
{
  "network": "devnet",
  "metadata": {
    "name": "My NFT",
    "symbol": "NFT",
    "description": "This is a sample NFT",
    "image": "https://example.com/nft-image.png"
  }
}
```

