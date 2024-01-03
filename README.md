# JavaScript Blockchain Implementation

This is a basic implementation of a blockchain using JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

## Introduction

This project implements a simple blockchain application in JavaScript.

## Features

1. Blockchain Functionality:
- Block Creation: Ability to create blocks containing transactions.
- Genesis Block: Initialization of the blockchain with a genesis block.
- Adding Blocks: Functionality to add new blocks to the blockchain.

2. Transaction Handling:
- Adding Transactions: Ability to add transactions between sender and recipient.
- Pending Transactions: Maintenance of pending transactions before mining.
- Processing Transactions: Processing pending transactions and adding them to blocks.

3. Cryptographic Operations:
- Generate Key Pair: Creation of public and private key pairs for encryption/decryption.
- Encrypt and Decrypt Messages: Capability to encrypt and decrypt messages using RSA encryption.

4. File Operations:
- Save Keys to Files: Saving generated keys (public and private) to files.
- Save Transactions to File: Recording transactions to a JSON file for storage.

5. User Interaction:
- Interactive CLI Interface: Utilization of Inquirer library for a command-line interface (CLI) to interact with users.
- Input Handling: Accepting user inputs for sender, recipient, messages, mining reward details, etc., via prompts.

6. Mining and Blockchain Operations:
- Proof-of-Work (PoW) Mining: Mining new blocks using a proof-of-work mechanism.
- Blockchain Integrity: Ensuring the integrity of the blockchain by linking blocks using hashes.
- Maintain Chain: Keeping track of the blockchain structure.

7. Logging and Feedback:
- Console Feedback: Providing feedback and logging messages in the console for key generation, transaction processing, and file operations.

8. Utility Functions:
- Hash Calculation: Computing hash values for blocks.
- Message Length Check: Verifying message length before encryption to prevent errors.

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Node.js and npm (Node Package Manager)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/samekeekz/blockchain-lab1.git
    ```
2. Initialize project:

    ```bash
    npm init -y
    ```
3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

1. Open your preferred code editor or Integrated Development Environment (IDE).

2. Run the project using Node.js:

    ```bash
    node --experimental-modules script.mjs
    ```

3. Follow the prompts or instructions provided in the terminal/console to interact with the blockchain application. This includes creating transactions, mining blocks, and exploring the blockchain.
