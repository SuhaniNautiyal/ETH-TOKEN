Project Title
Carmel Convent School Token (CCS)

Description
The Carmel Convent School Token (CCS) is a simple ERC20-like token implemented in Solidity. It allows users to mint new tokens and burn existing ones. The contract stores essential details about the token, including its name, abbreviation, and total supply. The token can be transferred by increasing or decreasing the balance of specific addresses.
Getting Started
Installing
Prerequisites:

Make sure you have Node.js and npm installed.
Install Truffle or Hardhat to test the contract.
Install MetaMask for managing accounts and interacting with the Ethereum network.
Install Ganache for running a local Ethereum blockchain.
Clone the Repository
Install Dependencies

Any modifications needed to be made to files/folders
Solidity Version: Ensure your environment uses Solidity 0.8.18 or later to avoid compatibility issues.
Contract Deployment: You may need to adjust the deployment script according to your development environment. Typically, this involves setting the correct network in the Truffle or Hardhat configuration.

Executing program
Compile the contract to check for errors.
Deploy the contract to a local or test network.
Use a script or a frontend to interact with the contract's mint and burn functions.
Verify the balance of addresses using the balances mapping.

Help

Insufficient Gas: Ensure you have enough gas to deploy or interact with the contract.
Balance Check: The burn function will fail if the address does not have enough tokens to burn. Make sure the balance is sufficient.
command to run if program contains helper info

Authors
Suhani Nautiyal
@SuhaniNautiyal
