﻿# ERC721 NFT Marketplace 

![GitHub release (latest by date)](https://img.shields.io/github/v/release/silviopaganini/nft-market?style=round)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=round)](https://github.com/prettier/prettier)
![GitHub](https://img.shields.io/github/license/silviopaganini/nft-market?style=round)
![](https://img.shields.io/badge/Typescript-💪-blue)


Prototype of a NFT Marketplace based on openZeppelin abstract upgradeable ERC721 contracts and Minting/uploading images to IPFS and integration with Opensea.io

## ⚙️ Dependencies

This project relies on [NFT Contracts](https://github.com/silviopaganini/nft-contracts) package and [NFT Lambda Service](https://github.com/silviopaganini/nft-market-service) for serving the metadata

## 🔬 Functionalities

1. Buy a pre-minted token.
2. Sell the token that was bought.
3. Transferring ETH to the previous token holder;
4. Adding and removing tokens from the marketplace;
5. Minting tokens;
6. Uploading NFT image to IPFS;
7. Metadata and marketplace on Opensea.io
8. Metadata and IPFS Lambda functions on AWS

<hr />


## ETH-USD Service

It's been transferred to the [NFT Lambda Service](https://github.com/silviopaganini/nft-market-service) repository.

## ⚡️ Tech-Stack

- Typescript
- Solidity
- React
- Truffle / Ganache
- Storybook
- openZeppelin
- Metamask (web3)
- Opensea.io
- Web3-react
- IPFS
- Lambda AWS
- serverless

## 🔧 .env file 

```
NODE_ENV=development
BROWSER=chrome
REACT_APP_SERVICE_URL=http://localhost:4000/dev
REACT_APP_RPC_URL_1=http://0.0.0.0:7545
REACT_APP_RPC_URL_4=https://rinkeby.infura.io/v3/INFURA_KEY

```


## 💰 Sponsor this project

Donations in ETH or SOL are welcome 

**ETH** `0xE9d7895Ed2e2df37e0476ea3532ba37d50CA2aD4`

**SOL** `9MDCiokkgs9vkv7GZoPDc6BoE8CaQm5ZQcDsQCPNZpQm`
