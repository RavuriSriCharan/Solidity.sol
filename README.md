## MyToken

This repository contains a simple Solidity smart contract named `MyToken`. This contract implements a basic token with minting and burning functionalities.

## Description

This project includes a creation of Token in remix editor which includes Mint and Burn function. The contract is written in Solidity, a programming language used for developing smart contracts on ethereum blockchain. The contract has two functions "burn" and "mint" for burnning and for minting the tokens. 

## Requirements

- Solidity ^0.8.18
- A development environment like Remix IDE 

### Contract Details

- "TokenName": Public variable storing the name of the token.
- "tokenAbbrv": Public variable storing the abbreviation of the token.
- "totalSupply": Public variable storing the total supply of the token.
- "balances": Mapping of addresses to their respective token balances.

## Functions

- "mint(address _address, uint _value)": Increases the total supply and the balance of the specified address.
- "burn(address _address, uint _value)": Decreases the total supply and the balance of the specified address, if the balance is greater than or equal to the value.

## Executing program


1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file named "MyToken.sol" and paste the contract code into it.
3. Compile the contract by selecting the appropriate Solidity compiler version (^0.8.18).
4. Deploy the contract:
   - Go to the "Deploy & Run Transactions" tab.
   - Ensure the environment is set to "JavaScript VM" (or any other preferred environment).
   - Click the "Deploy" button.
5. Interact with the contract:
   - Once deployed, you can see the deployed contract under "Deployed Contracts".
   - Use the available functions ("mint" and "burn") to interact with the contract.
 


## Authors

Sri charan



## License

This project is licensed under the Sri charan License - see the LICENSE.md file for details
