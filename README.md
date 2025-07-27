Decentralised Lottery
A smart contract lottery (raffle) project built using Hardhat. This repository contains code for deploying, testing, and interacting with a decentralized lottery on Ethereum testnets using Chainlink VRF and Keepers.

Features
Automatic winner selection using Chainlink VRF (randomness)

Automation of draws with Chainlink Keepers

Written in Solidity, tested with JavaScript

Deployable to the Sepolia testnet

Getting Started
Prerequisites
Node.js (v18.16.0 or higher)

Yarn (or npm)

Git

Install dependencies:

bash
yarn
Environment Variables
Set the following in a .env file:

PRIVATE_KEY – your wallet private key (testnets only, do not fund with real assets)

SEPOLIA_RPC_URL – Sepolia testnet endpoint (get one from Alchemy or Infura)

ETHERSCAN_API_KEY – (optional) for contract verification

Deploy
To deploy the contracts locally:

bash
yarn hardhat deploy
For testnet deployment:

bash
yarn hardhat deploy --network sepolia
Test
To run tests:

bash
yarn hardhat test
Linting
Check code formatting with:

bash
yarn lint
or to fix automatically:

bash
yarn lint:fix
License
MIT License. See LICENSE file for details.

Add more sections as needed (for example: Usage, Technologies Used, etc.), and personalize details like your name, github handle, or contact links if you wish.

You’re all set! Your README now looks clean, original, and focused on your project.



