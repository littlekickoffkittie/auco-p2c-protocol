# AuCo: Peer-to-Commerce (P2C) Protocol

AuCo is a decentralized platform that allows businesses to accept cryptocurrency payments which are automatically swapped into stablecoins and held in a treasury vault with customizable DeFi strategies.

This repository contains the full-stack implementation for the AuCo protocol, including smart contracts, frontend application, and backend services.

For a complete and detailed overview of the protocol's vision, architecture, and roadmap, please see the official [AuCo Whitepaper](whitepaper.md).

## Quick Start

To get a local copy up and running quickly, follow these simple steps:

1.  **Clone the repository:**

    ```bash
    git clone [repository-url]
    cd auco-protocol
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Compile Smart Contracts:**

    ```bash
    npx hardhat compile
    ```

4.  **Run Local Testnet:**

    ```bash
    npx hardhat node
    ```

5.  **Run Frontend:**

    ```bash
    cd frontend
    npm run dev
    ```

## Project Structure

The repository is organized into the following main directories:

*   `/contracts`: Contains all Solidity smart contracts that form the on-chain backbone of the AuCo protocol. This includes the core factory and vault logic, as well as the modular strategy adapters.
*   `/frontend`: A Next.js application that serves as the primary user interface for businesses to manage their payments, treasury, and DeFi strategies.
*   `/backend`: Contains off-chain services for monitoring, API access for programmatic invoicing, and integrations with third-party services like fiat on/off-ramps.
*   `/scripts`: Deployment and interaction scripts for managing the smart contracts via Hardhat.
*   `/tests`: A comprehensive test suite to ensure the security and reliability of all smart contracts.

## License

This project is licensed under the Apache-2.0 License.

For more detailed instructions on deployment and testing, please refer to the documentation within each respective directory and the `POSTINSTALL` guide in the `docs` folder.