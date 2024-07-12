# ERC20 Token Project

This project demonstrates the creation, deployment, and interaction with an ERC20 token using HardHat. The token contract allows the owner to mint tokens to a provided address, and any user can burn and transfer tokens.

## Prerequisites

Ensure you have the following installed:

- Node.js and npm: [Download Node.js](https://nodejs.org/)
- Git: [Download Git](https://git-scm.com/)

## Setup

1. Clone the repository and navigate into the project directory:

    ```bash
    git clone https://github.com/your-username/erc20-token.git
    cd erc20-token
    ```

2. Install the necessary dependencies:

    ```bash
    npm install
    ```

## Project Structure

- `contracts/MyToken.sol`: The ERC20 token contract.
- `scripts/deploy.js`: Script to deploy the contract.
- `scripts/interact.js`: Script to interact with the deployed contract.
