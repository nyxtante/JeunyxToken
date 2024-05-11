# JeunyxToken - Simple Token Project

This Solidity program is a simple token contract that allows for the minting and burning of tokens. The purpose of this contract is to provide a basic implementation of a token on the Ethereum blockchain.

## Description

This contract, written in Solidity, enables the creation of a token named "Jeunyx" with the symbol "Jnyx". It includes functionality for minting new tokens and burning existing tokens. The contract maintains a mapping of token balances for each address. This project serves as a foundational example for understanding how to create and interact with tokens on the Ethereum blockchain.

## Getting Started

### Executing program

To deploy and interact with this contract, you can use Remix, an online Solidity IDE. Follow these steps:

1. Go to the Remix website at [https://remix.ethereum.org/](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).
3. Copy and paste the provided Solidity code into the file.
4. Compile the code by clicking on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile MyToken.sol" button.
5. Deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.
6. Once the contract is deployed, you can interact with it by calling the `mint` and `burn` functions.

### Example:
```solidity
// Mint 100 tokens to an address
mint(address _address, uint _value);

// Burn 50 tokens from an address
burn(address _address, uint _value);

## Authors: Cargel Jeunyx P. Militante
   Facebook: Jeu Nyx Cargel (www.facebook.com/nyxtante)

   ## License

This project is licensed under the MIT License - see the LICENSE.md file for details
