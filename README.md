# Blockchain-Based Land Registry System

## Introduction
The **Blockchain-Based Land Registry System** is a decentralized application (DApp) designed to securely manage and verify land ownership and transactions. Leveraging blockchain technology, this system ensures transparency, immutability, and efficiency in land record management, reducing dependency on intermediaries and minimizing fraudulent activities.

## Key Features
- **Tamper-Proof Ownership Records**: All property records are securely stored on a blockchain ledger, preventing unauthorized modifications.
- **Permanent and Verifiable Transactions**: Once a record is added, it remains immutable, ensuring an indisputable history of land ownership.
- **Efficient and Decentralized Transactions**: Buyers and sellers can engage in secure property transfers without reliance on centralized authorities.
- **Automated Smart Contracts**: Predefined conditions in smart contracts ensure secure and self-executing land transactions.
- **Transparent and Trustworthy System**: Transactions are visible to authorized network participants, enhancing trust in the process.

## System Interface
![System Interface]![landregister png](https://github.com/user-attachments/assets/a86a912d-fcb1-4d1b-abfd-20b467c92761)


## Functionalities
- **Property Registration**: Users can register land by submitting key details such as location, size, and ownership credentials.
- **Ownership Transfer**: Transactions between buyers and sellers are validated and executed using smart contracts.
- **Land Record Search**: Users can query property details through a unique identifier like a Land ID.

## Technology Stack
- **Blockchain Network**: Ethereum for decentralized data storage and security.
- **Smart Contract Development**: Implemented using Solidity.
- **Backend Infrastructure**: Truffle framework for contract management.
- **Frontend Development**: Built with HTML, CSS, and JavaScript, utilizing **Web3.js** for blockchain interactions.

## Setup and Deployment
### Prerequisites
1. Install [Node.js](https://nodejs.org/) for managing project dependencies.
2. Download and set up [Truffle](https://www.trufflesuite.com/truffle), a development framework for Ethereum smart contracts.
3. Install [Ganache](https://www.trufflesuite.com/ganache) to create a local Ethereum blockchain for testing purposes.

### Steps to Launch the Project
1. Clone the repository to your system.
2. Navigate to the project directory in the terminal.
3. Run `npm install` to install necessary dependencies.
4. Start Ganache to initiate a local Ethereum blockchain.
5. Compile smart contracts using `truffle compile`.
6. Deploy contracts to the blockchain using `truffle migrate`.
7. Open the frontend using a local HTTP server (e.g., Live Server in VS Code) to interact with the application.
