# Foundry NFT

[![Build Status](https://img.shields.io/github/actions/workflow/status/Steiner-254/foundry-nft/ci.yml?branch=master)](https://github.com/Steiner-254/foundry-nft/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A Foundry-based NFT smart contract project written in Solidity. This repository provides a robust template for developing, testing, and deploying NFT contracts using Foundry.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Clone the Repository](#clone-the-repository)
  - [Install Foundry](#install-foundry)
  - [Install Dependencies](#install-dependencies)
  - [Configure Environment Variables](#configure-environment-variables)
- [Usage](#usage)
  - [Building the Project](#building-the-project)
  - [Running Tests](#running-tests)
  - [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The **Foundry NFT** project is a starting point for NFT smart contract development. Leveraging the power of the Foundry toolchain, this project streamlines the process of building, testing, and deploying Solidity contracts. Whether you are a beginner or an experienced developer, this repository provides a solid framework to kickstart your NFT project.

## Features

- **Solidity-based Contracts:** All contracts are written in Solidity.
- **Foundry Integration:** Use Foundry’s `forge` commands to compile, test, and deploy contracts.
- **Automated Testing:** Extensive test suite located in the `test` folder.
- **Deployment Scripts:** Deployment scripts are available in the `script` folder.
- **Continuous Integration:** GitHub Actions workflows are set up for automated testing and linting.
- **Environment Configuration:** Sample environment variables provided in `.env.example`.

## Prerequisites

- [Foundry](https://book.getfoundry.sh/) – Ethereum development toolchain.
- [Git](https://git-scm.com/) – For version control.
- [Node.js](https://nodejs.org/) (optional) – If you plan to interact with the project using JavaScript-based tools.
- A code editor of your choice (e.g., [VS Code](https://code.visualstudio.com/)).

## Installation

### Clone the Repository

```bash
git clone https://github.com/Steiner-254/foundry-nft.git
cd foundry-nft
```

### Install Foundry
- If you haven’t installed Foundry yet, run:

```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

### Install Dependencies
- If your project requires additional dependencies from the lib directory, ensure they are updated:

```bash
forge install
```

### Configure Environment Variables
- Copy the example environment file and adjust the values as needed:

```bash
cp .env.example .env
```

## Usage
### Building the Project
- To compile the Solidity contracts, run:

```bash
forge build
```

### Running Tests
- Execute the test suite to ensure everything is working as expected:

```bash
forge test
```

### Deployment
- Deployment scripts are available in the script folder. To deploy your NFT contract, run:

```bash
forge script script/DeployNFT.s.sol --broadcast --verify
```

>> (Make sure you have configured your network settings and private keys as needed.)


### Project Structure
- **src/:** Contains all Solidity source contracts.
- **test/:** Contains unit tests for the contracts.
- **script/:** Deployment and utility scripts.
- **lib/:** External libraries and dependencies.
- **.github/workflows/:** CI/CD configurations for GitHub Actions.
- **Makefile:** Command shortcuts for common tasks.
- **foundry.toml:** Configuration file for Foundry.
- **.env.example:** Example file for environment variables.

## License 📜
- This project is licensed under the MIT License. See the LICENSE file for details.

### Contributing 🤝
- Project Developed By: [Steinet254](https://twitter.com/Steiner254)
- Feel free to fork this repo, submit issues, or create pull requests! Contributions are always welcome.

### Acknowledgments 🙌
- `Foundry` for providing an exceptional framework for Solidity development.
- `OpenZeppelin` for setting standards in secure contract implementations.
- `Ethereum Community` for supporting decentralized application development.
- `Cyfrin Updraft` for the learning content aiding to this project development.

### Happy Coding! 🚀

```vbet
Happy Web3 Revolution <3
```
