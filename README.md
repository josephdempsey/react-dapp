# Basic example of a solidity smart contract.

Gives you a good idea of what you could achieve with smart contracts. 

## Getting started

Here's how to deploy this project locally and with Hardhat and deploy a contract to the network.

1. Clone the repo

2. Install the dependencies

```sh
npm install
```

3. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

6. Run the app

```sh
npm start
```

Thanks to https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13 for the tutorial.