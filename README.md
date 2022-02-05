# NFT Marketplace

Create, buy and sell NFTs on Ethereum and Polygon.

Inspired by Nader Dabit's tutorial, [Building a Full Stack NFT Marketplace on Ethereum with Polygon ](https://dev.to/dabit3/building-scalable-full-stack-apps-on-ethereum-with-polygon-2cfb)

## Quicktstart

```sh
yarn install
yarn dev
```

## Deploy your Smart Contracts

Spin up a local network to get some practice wallets and private keys

`npx hardhat node`

Deploy your contract: `npx hardhat run scripts/deploy.js --network localhost`

Replace `localhost` with `mumbai` to run on Polygon