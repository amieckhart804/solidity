# The Solidity Contract-Oriented Programming Language

[![Matrix Chat](https://img.shields.io/badge/Matrix%20-chat-brightgreen?style=plastic&logo=matrix)](https://matrix.to/#/#ethereum_solidity:gitter.im)
[![Gitter Chat](https://img.shields.io/badge/Gitter%20-chat-brightgreen?style=plastic&logo=gitter)](https://gitter.im/ethereum/solidity)
[![Solidity Forum](https://img.shields.io/badge/Solidity_Forum%20-discuss-brightgreen?style=plastic&logo=discourse)](https://forum.soliditylang.org/)
[![X Follow](https://img.shields.io/twitter/follow/solidity_lang?style=plastic&logo=x)](https://X.com/solidity_lang)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/000335908?domain=https%3A%2F%2Ffosstodon.org%2F&logo=mastodon&style=plastic)](https://fosstodon.org/@solidity)

You can talk to us on Gitter and Matrix, tweet at us on X (previously Twitter), or create a new topic in the Solidity forum. Questions, feedback, and suggestions are welcome!

Solidity is a statically typed, contract-oriented, high-level language for implementing smart contracts on the Ethereum platform.

For a comprehensive overview and starting point, please check out the official [Solidity Language Portal](https://soliditylang.org).

## Table of Contents

- [Background](#background)
- [Build and Install](#build-and-install)
- [Example](#example)
- [Documentation](#documentation)
- [Development](#development)
- [Maintainers](#maintainers)
- [License](#license)
- [Security](#security)

## Background

Solidity is a statically-typed curly-braces programming language designed for developing smart contracts
that run on the Ethereum Virtual Machine (EVM). Smart contracts are programs executed inside a peer-to-peer
network where no single entity has special authority over execution, enabling decentralized applications for tokens of value,
ownership, voting, and other kinds of logic.

When deploying contracts, always use the latest released version of
Solidity. This is because breaking changes, new features, and bug fixes are introduced regularly. We currently use a 0.x version
number [to indicate this fast pace of change](https://semver.org/#spec-item-4).

## Build and Install

Instructions for building and installing the Solidity compiler can be
found in the [Solidity documentation](https://docs.soliditylang.org/en/latest/installing-solidity.html#building-from-source).

## Example

A "Hello World" program in Solidity:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity >=0.6.0 <0.9.0;

contract HelloWorld {
    function helloWorld() external pure returns (string memory) {
        return "Hello, World!";
    }
}
