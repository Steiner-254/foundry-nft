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

