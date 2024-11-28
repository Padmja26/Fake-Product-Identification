Fake Product Identification using Blockchain

This project leverages blockchain technology to authenticate products and combat counterfeiting. It uses Truffle, Ganache, and Solidity for smart contract deployment and Web3.js for interacting with the blockchain.

Packages Required
Truffle: v5.6.7
Ganache: v7.5.0
Solidity: v0.5.16
Node.js: v15.8.0
Web3.js: v1.7.4
npm: v7.5.1
Other Requirements
Chromium-based browser (e.g., Chrome)
MetaMask browser extension

Setup Process
1. Clone the Project
git clone https://github.com/A4ANK/Fake-Product-Identification.git

3. Install Dependencies
Navigate to the project folder and run:

npm install
3. Compile Contracts

Compile the smart contract source files using Truffle:

truffle compile


4. Set Up Local Blockchain with Ganache
   
Open Ganache and create a new workspace.
Add truffle-config.js as a project.
Set the server port to 7545 (same as in truffle-config.js).

6. Configure MetaMask
Open MetaMask in Chrome and create a new test network:
Network ID: 5777 (from Ganache)
RPC Server: http://127.0.0.1:8545
Chain Code: 1337
Import an account using the private key of any Ganache account.
7. Deploy Contracts
Run migrations to deploy contracts on the local blockchain:

truffle migrate
7. Start the Server
Launch the server to open the homepage:

npm run dev
8. Interact with the Web Application
Login to MetaMask and connect the added account to the local blockchain (localhost:3000).
Use the website to interact with deployed smart contracts.
