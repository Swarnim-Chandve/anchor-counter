# Anchor Counter

An on-chain counter program built using [Anchor](https://project-serum.github.io/anchor/), a framework for Solana smart contracts.

## Overview

This project implements a simple counter program on the Solana blockchain. The program supports initializing a counter, incrementing the counter, and decrementing the counter. Each action is recorded on-chain, providing an example of state management using Solana's blockchain.

## Features

- **Initialize**: Creates a new counter with an initial count of 0.
- **Increment**: Increases the counter by 1.
- **Decrement**: Decreases the counter by 1.

## Project Structure

- `programs/anchor_counter/src/lib.rs`: Contains the Rust code for the Solana program.
- `tests/anchor_counter.js`: Contains JavaScript tests to interact with the Solana program using Anchor framework.
- `migrations/deploy.js`: Script to deploy the program.

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Anchor CLI](https://project-serum.github.io/anchor/getting-started/installation.html)
- Node.js and npm

### Building the Program

1. Clone the repository:
   ```bash
   git clone https://github.com/Swarnim-Chandve/learning-solana.git
   cd learning-solana
### Build the Solana program:
 ```bash
anchor build
```
### Deploy the program to the Solana devnet:
 ```bash
anchor deploy
```

