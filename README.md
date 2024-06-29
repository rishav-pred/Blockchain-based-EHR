# Blockchain-Based Electronic Health Record (EHR) System
Access the webiste here : https://rishav-pred.github.io/Blockchain-based-EHR/
[medical_record_project](index.html)

Welcome to the Blockchain-Based Electronic Health Record (EHR) System! This system leverages Ethereum blockchain technology and Solidity smart contracts to provide a secure, decentralized, and transparent platform for managing electronic health records.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Smart Contracts](#smart-contracts)
- [Contributing](#contributing)
- [License](#license)


## Introduction
The Blockchain-Based EHR System aims to enhance the security and accessibility of health records by utilizing blockchain technology. By storing health records on a decentralized ledger, the system ensures data integrity, privacy, and accessibility for authorized users.

## Features
Decentralized Storage: Health records are stored on the Ethereum blockchain, ensuring data integrity and availability.
Security and Privacy: Access to health records is controlled through smart contracts, providing robust security and privacy controls.
Transparency: All transactions and access logs are recorded on the blockchain, ensuring transparency and traceability.
Interoperability: The system supports integration with existing health record management systems.
Architecture
The system consists of the following components:

Ethereum Blockchain: The decentralized ledger where health records and transactions are stored.
Smart Contracts: Written in Solidity, these contracts manage the creation, storage, and access control of health records.
Frontend Application: A web-based interface for users to interact with the system.
Backend Services: Node.js services that facilitate communication between the frontend and the blockchain.
Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js and npm installed
Truffle Suite for managing smart contracts
Ganache for local Ethereum blockchain simulation
Metamask for managing Ethereum accounts and transactions

## Installation
Clone the Repository
```bash
git clone https://github.com/rishav-pred/Blockchain-based-EHR.git
cd Blockchain-based-EHR
```


# 1. Install Dependencies
``` bash
npm install
```

# 2. Compile Smart Contracts
``` bash
truffle compile
```
# 3. Deploy Smart Contracts
``` bash
truffle migrate --network development
```

# 4. Run the Application
``` bash
npm start
```

## Usage
Open the Application
Open your web browser and navigate to http://localhost:3000.

# Create an Account
Use Metamask to create and connect your Ethereum account.

# Access Health Records
Use the web interface to create, view, and manage health records. Access controls and permissions are managed through smart contracts.

## Smart Contracts
The smart contracts are located in the contracts directory. Key contracts include:

HealthRecord.sol: Manages the creation and storage of health records.
AccessControl.sol: Controls access permissions for health records.
UserRegistry.sol: Maintains a registry of authorized users.

## Contributing
We welcome contributions to the Blockchain-Based EHR System! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeature).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeature).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.Welcome to the Blockchain-Based Electronic Health Record (EHR) System! This system leverages Ethereum blockchain technology and Solidity smart contracts to provide a secure, decentralized, and transparent platform for managing electronic health records.

