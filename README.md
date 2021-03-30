# ETHEREUM PET SHOP

This is a DAPP (Decentralized Application) that I've followed in the tutorial from Truffle suite (https://www.trufflesuite.com/tutorials/pet-shop).

The tutorial provides step by step to building the smart contracts on Ethereum via local network, by [Ganache](https://www.trufflesuite.com/ganache).

## Required Tools/Library
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview)
- [Ganache](https://www.trufflesuite.com/ganache)
- [Node.js](https://nodejs.org/en/)
- [Metamask](https://metamask.io/)

## Preparation
1. Install Node.js
2. Install Truffle node package
3. Install Ganache
4. Install Metamask

## How to Run

### Ethereum smart contract
** run Ganache first **

- compile the smart contract

    ```
    $ truffle compile
    ```
- test the smart contract

    ```
    $ trffle test
    ```
- deploy the smart contract

    ```
    $ truffle migrate
    ```

### Web Application
```
$ npm install

$ npm run dev
```