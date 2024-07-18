# Decentralized-Crypto-Asset-Transfer-System

## Description
This project aims to create a system that brings order to the process of transferring cryptocurrency assets to the surviving beneficiaries of the deceased. In the cryptocurrency world, the traditional system of wills and testaments is non-existent, and given the anonymity and decentralized nature of the ecosystem, the asset transfer process is a significant concern. This project was built during the Sentinel Hacks event at KSIT in May 2023.

## The Problem
- After the demise of a person, the transfer of their assets is governed by the laws and interpretations of the person's will.
- In the cryptocurrency domain, where there is no centralized institution or body that codifies the regulations, it becomes challenging to identify and regulate the transfer of crypto assets.

## Technology Stack
**Web Application**
- Flask (Python)
- HTML
- CSS

**Blockchain**
- Ethereum
- Ganache
- Web3
- Solidity

## Getting Started
1. Install the required modules, such as Flask, Web3, and others as applicable.
2. Run the application using the following command:
    ```bash
    python main.py
    ```

## File Structure
- **contract.py**: The runnable file that hosts the application.
- **contract.json**: The contract details and beneficiary information.

## Problems with the Traditional System
- Lack of due execution (procedural inadequacy)
- Lack of testamentary intention and capacity
- Undue influence
- Fraud or forgery
- Revocation claims by family

## Solution
The project proposes a novel solution that considers the unique challenges of cryptocurrency assets. It introduces the following key features:
- **Time-lock**: The assets can be locked for a certain period, after which they are transferred. The owner can modify the lock duration while still alive.
- **Key-lock**: A two-key system is used for asset transfer. The first key is shared among the beneficiaries, preventing unauthorized access. The second key is held by a trusted source or contract, which determines the proportion of inheritance to be received.

## Working and Features
- The application implements the time-lock and key-lock mechanisms to ensure a balanced and secure transfer of crypto assets upon the owner's demise.
- It provides a web-based interface for managing the asset transfer process.

## Snapshots of the Working Web Application
![Screenshot 1][] ![Screenshot 2][]

## Challenges and Acknowledgements
The team faced issues in the integration of the blockchain and the Python application.

## Further Enhancements
- Methods to validate the occurrence of the event of death.
- Secure third-party for preserving the validity of the keys.

## Team
- Sujan Reddy: [https://github.com/sujan-reddy](https://github.com/sujan-reddy)
- Shraddha C: [https://github.com/Shraddhac-14](https://github.com/Shraddhac-14)
- N. Dharshan: [https://github.com/NDharshan](https://github.com/NDharshan)
