# Foundry Projects

Welcome to the Foundry Projects repository! This monorepo contains smart contract projects and protocols built while completing the **[Cyfrin Updraft](https://updraft.cyfrin.io/)** Advanced Foundry curriculum.

## Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Projects](#projects)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Overview

This repository serves as a centralized monorepo for all smart contract projects developed during the **[Cyfrin Updraft](https://updraft.cyfrin.io/)** Foundry curriculum. Each directory represents a standalone project (managed as Git submodules) showcasing various Solidity and Foundry concepts—ranging from basic storage and DeFi protocols to account abstraction, upgradeable contracts, and on-chain DAOs.

## Getting Started

To get started with the Foundry Project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone --recurse-submodules https://github.com/Eunum56/foundry.git
   cd foundry
   ```

2. **Initialize and update submodules:**
   If you've already cloned the repository, initialize and update the submodules:

   ```bash
   git submodule update --init --recursive
   ```

3. **Install Dependencies:**
   Each project may have its own dependencies listed in the respective `README.md` files. Make sure to install them as needed.

## Projects

### Foundry Simple Storage

- Path: `foundry-simple-storage/`
- Description: A simple storage contract example using Foundry.
- Repository: [foundry-simple-storage](https://github.com/Eunum56/foundry-simple-storage.git)

### Foundry Fund Me

- Path: `foundry-fund-me/`
- Description: A Simple fund-me example using Foundry.
- Repository: [foundry-fund-me](https://github.com/Eunum56/foundry-fund-me.git)

### Foundry Lottery

- Path: `foundry-lottery/`
- Description: A Simple Lottery project example using Foundry.
- Repository: [foundry-lottery](https://github.com/Eunum56/foundry-lottery.git)

### Foundry ERC20

- Path: `foundry-ERC20/`
- Description: A Simple ERC20 Standard (Build from scratch) example using Foundry.
- Repository: [foundry-ERC20](https://github.com/Eunum56/foundry-ERC20.git)


### Foundry ERC721(NFT)

- Path: `foundry-NFT-From-Scratch/`
- Description: A Simple ERC721(NFT) standard (Build from scratch) example using Foundry.
- Repository: [foundry-NFT-From-Scratch](https://github.com/Eunum56/foundry-NFT-From-Scratch.git)


### Foundry NFT

- Path: `foundry-nft/`
- Description: A Simple NFT ERC721 project example using Foundry.
- Repository: [foundry-nft](https://github.com/Eunum56/foundry-nft.git)

### Foundry DeFi StableCoin

- Path: `foundry-DeFi-stablecoin/`
- Description: A Simple DeFi StableCoin pegged project example using Foundry.
- Repository: [foundry-DeFi-stablecoin](https://github.com/Eunum56/foundry-DeFi-stablecoin.git)

### Foundry Rebase Token

- Path: `foundry-Rebase-Token/`
- Description: A Simple Rebase Token project example using Foundry.
- Repository: [foundry-Rebase-Token](https://github.com/Eunum56/foundry-Rebase-Token.git)

### Foundry Merkle Airdrop

- Path: `foundry-Merkle-Airdrop/`
- Description: A Simple Merkle Airdrop(ERC20) project example using Foundry.
- Repository: [foundry-Merkle-Airdrop](https://github.com/Eunum56/foundry-Merkle-Airdrop.git)

### Foundry SC Upgrades

- Path: `foundry-SC-Upgrades/`
- Description: A Simple Upgradable Smart Contract project example using Foundry.
- Repository: [foundry-SC-Upgrades](https://github.com/Eunum56/foundry-SC-Upgrades.git)


### Foundry Account Abstraction

- Path: `foundry-Account-Abstraction/`
- Description: A Simple Account Abstraction on Ethereum and ZKSync network project example using Foundry.
- Repository: [foundry-Account-Abstraction](https://github.com/Eunum56/foundry-Account-Abstraction.git)

### Foundry DAO

- Path: `foundry-dao/`
- Description: A Simple on-chain DAO (Decentralized Autonomous Organization) project example using Foundry.
- Repository: [foundry-dao](https://github.com/0xEunum/foundry-dao)


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Create a pull request.

## Acknowledgments

Special thanks to **[Cyfrin Updraft](https://updraft.cyfrin.io/)** and **[Patrick Collins](https://github.com/PatrickAlphaC)** for providing an exceptional, free, and in-depth Web3 education curriculum covering Foundry fundamentals and advanced smart contract development.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
