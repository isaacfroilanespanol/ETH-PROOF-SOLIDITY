ESPANOL Token Contract

This is a Solidity smart contract for the ESPANOL token (ISAAC). The ESPANOL token is an ERC-20 compatible token implemented on the Ethereum blockchain.

SPDX-License-Identifier

This code is licensed under the MIT License. For more details, please refer to the LICENSE file.

Prerequisites

Solidity 0.8.18 or compatible version
Contract Details

The ESPANOL contract includes the following public variables:

tokenName: A string representing the name of the token ("ESPANOL").

tokenAbbrv: A string representing the abbreviation of the token ("ISAAC").

totalSupply: An unsigned integer representing the total supply of the ESPANOL token.

Additionally, the contract utilizes a mapping variable:

balances: A mapping that associates Ethereum addresses with their corresponding ESPANOL token balances.

Functions

mint(address _address, uint _value)

This function is used to mint new ESPANOL tokens and assign them to a specified address. It takes two parameters:

_address: The address to which the newly minted tokens will be assigned.

_value: The number of tokens to mint.

The function increases the total supply by the specified value and updates the balance of the target address accordingly.

burn(address _address, uint _value)

This function is used to burn (destroy) existing ESPANOL tokens from a specified address. It takes two parameters:

_address: The address from which the tokens will be burned.

_value: The number of tokens to burn.

The function checks if the address has a sufficient balance to burn the specified amount. If so, it reduces the total supply and updates the balance of the address accordingly.

Please note that burning tokens is a permanent action and cannot be undone.

Usage

To utilize this contract, follow these steps:

1.Install a compatible Solidity compiler.
2.Compile the contract using the Solidity compiler.
3.Deploy the contract to the Ethereum blockchain.
4.Interact with the contract by calling the mint and burn functions.

Please ensure that you have a basic understanding of Solidity and the Ethereum blockchain before deploying and interacting with smart contracts.

Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

License

This code is licensed under the terms of the MIT License. See the LICENSE file for more information.
