:warning: This repository is not maintained. Please see: https://github.com/airswap/airswap-protocols

# AirSwap Contracts

This repository includes AirSwap exchange and token smart contracts. Using [Truffle](http://truffleframework.com/) for development and testing.

## Bug Bounty

We're running an ongoing bug bounty. Details on the [AirSwap blog](https://blog.airswap.io/smart-contracts-and-bug-bounty-ad75733eb53f). To browse prior submissions, please see [submissions.md](https://github.com/airswap/contracts/blob/master/submissions.md).

## Getting Started

Use Yarn or NPM to install dependencies.
```
yarn install -g truffle
yarn install -g ethereumjs-testrpc
yarn install
```

To test, first run a testrpc instance.
```
testrpc
```
Then, run the Truffle test command.
```
truffle test
```
