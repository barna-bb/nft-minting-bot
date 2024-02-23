# Simple NFT Minting Bot

## Description
A simple script of an NFT batch minting bot. It can be modified to work as part of a more robust node program or executed as a simple bash script. It needs to be configured to work for a specific NFT project, since the minting functions of the contracts are usually given different names. These can be checked by using tools such as [Etherscan](https://etherscan.io/). The volume and other arguments can also be easily configured.

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Web3](https://web3js.readthedocs.io/en/v1.5.2/) (Blockchain Interaction)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview) (Development Framework)
- [Ganache](https://www.trufflesuite.com/ganache) (For Local Blockchain)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Truffle](https://www.trufflesuite.com/docs/truffle/overview), In your terminal, you can check to see if you have truffle by running `truffle version`. To install truffle run `npm i -g truffle`. Ideal to have truffle version 5.4 to avoid dependency issues.
- Install [Ganache](https://www.trufflesuite.com/ganache).

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd nft_batch_minting
$ npm install 
```

### 3. Start Ganache
`$ ganache`

### 4. Migrate Smart Contracts
`$ truffle migrate --reset`

### 5. Run Batch Script
`$ node ./scripts/mint.js`

## Acknowledgement
This project is based on a tutorial by [DApp University](https://www.youtube.com/@DappUniversity)
