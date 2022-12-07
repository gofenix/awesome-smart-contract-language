# Awesome Smart Contract Language [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zhenfeng-zhu/awesome-smart-contract-language)

---

A collection of awesome blockchain [smart contract](https://en.wikipedia.org/wiki/Smart_contract) languages, resources and shiny things.

# Solidity

[https://github.com/ethereum/solidity](https://github.com/ethereum/solidity)

Solidity is a statically typed, contract-oriented, high-level language for implementing smart contracts on the Ethereum platform.

# Move

[https://github.com/move-language/move](https://github.com/move-language/move)

Move is a programming language for writing safe smart contracts originally developed at Facebook to power the Diem blockchain. Move is designed to be a platform-agnostic language to enable common libraries, tooling, and developer communities across diverse blockchains with vastly different data and execution models. Move's ambition is to become the "JavaScript of web3" in terms of ubiquity--when developers want to quickly write safe code involving assets, it should be written in Move.

# Vyper

[https://github.com/vyperlang/vyper](https://github.com/vyperlang/vyper)

Vyper is a contract-oriented, pythonic programming language that targets the [Ethereum Virtual Machine (EVM)](https://ethereum.org/learn/#ethereum-basics).

# ink!

[https://github.com/paritytech/ink](https://github.com/paritytech/ink)

ink! is an [eDSL](https://wiki.haskell.org/Embedded_domain_specific_language) to write smart contracts in Rust for blockchains built on the [Substrate](https://github.com/paritytech/substrate) framework. ink! contracts are compiled to WebAssembly.

# fe

[https://github.com/ethereum/fe](https://github.com/ethereum/fe)

Fe is an emerging smart contract language for the Ethereum blockchain.

Fe is a statically typed language for the Ethereum Virtual Machine (EVM). It is inspired by Python and Rust which makes it easy to learn -- especially for new developers entering the Ethereum ecosystem.

# Sway

[https://github.com/FuelLabs/sway](https://github.com/FuelLabs/sway)

Sway is a language developed for the Fuel blockchain. It is heavily inspired by Rust and aims to bring modern language development and performance to the blockchain ecosystem.

# Cadence

[https://github.com/onflow/cadence](https://github.com/onflow/cadence)

Cadence is a resource-oriented programming language that introduces new features to smart contract programming that help developers ensure that their code is safe, secure, clear, and approachable.

# Cairo 1.x

[https://github.com/starkware-libs/cairo](https://github.com/starkware-libs/cairo)

Cairo is the first Turing-complete language for creating provable programs for general computation.

Cairo becomes Rusty! Check by yourself!

# Cairo 0.x

[https://github.com/starkware-libs/cairo-lang](https://github.com/starkware-libs/cairo-lang)

**StarkNet** is a permissionless decentralized ZK-Rollup operating as an L2 network over Ethereum, where any dApp can achieve unlimited scale for its computation, without compromising Ethereum’s composability and security.

**Cairo** is a programming language for writing provable programs, where one party can prove to another that a certain computation was executed correctly. **Cairo** and similar proof systems can be used to provide scalability to blockchains.

StarkNet uses the **Cairo** programming language both for its infrastructure and for writing StarkNet contracts.

# Rust

[https://github.com/rust-lang/rust](https://github.com/rust-lang/rust)

Empowering everyone to build reliable and efficient software.

- [Solana-Rust](https://docs.solana.com/developing/on-chain-programs/developing-rust)
- [CosmWasm](https://cosmwasm.com/)
- [iotex](https://github.com/iotexproject/iotex-core)

# Motoko

[https://github.com/dfinity/motoko](https://github.com/dfinity/motoko)

A safe, simple, actor-based programming language for authoring [Internet Computer](https://internetcomputer.org/) (IC) canister smart contracts.

# BitcoinScript

[https://en.bitcoin.it/wiki/Script](https://en.bitcoin.it/wiki/Script)

Bitcoin uses a scripting system for transactions. Forth-like, Script is simple, stack-based, and processed from left to right. It is intentionally not Turing-complete, with no loops.

A script is essentially a list of instructions recorded with each transaction that describe how the next person wanting to spend the Bitcoins being transferred can gain access to them. The script for a typical Bitcoin transfer to destination Bitcoin address D simply encumbers future spending of the bitcoins with two things: the spender must provide

1. a public key that, when hashed, yields destination address D embedded in the script, and
2. a signature to prove ownership of the private key corresponding to the public key just provided.

# Zinc

[https://github.com/matter-labs/zinc](https://github.com/matter-labs/zinc)

Zinc is an emerging framework for developing smart contracts and SNARK circuits on the zkSync platform.
