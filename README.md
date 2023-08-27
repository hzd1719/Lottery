# Proveably Random Raffle Contracts

## About

This code is designed to create a provably random smart contract lottery.

## What do we want it to do?

1. Users can enter by paying for a ticket.
   1.1. The ticket fees will be awarded to the winner during the draw.

2. After X period of time, the lottery will automatically select a winner.
   2.1. This will be done programmatically.

3. Using Chainlink VRF & Chainlink Automation.
   3.1. Chainlink VRF -> Randomness
   3.2. Chainlink Automation -> Time-based trigger


## Foundry

**Foundry is a blazingly fast, portable, and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat, and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions, and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
