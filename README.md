# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
# Project setup

```shell
npx create-react-app Folder-name
npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers
npx hardhat
```
# Hardhat config
```shell
module.exports = {
  solidity: "0.8.4",
  paths: {
    artifacts:'./src/artifacts'
  },
  //config for hardhat local network
  networks: { 
    hardhat:{
      chainId: 1337
    }
  }
};
 ```

