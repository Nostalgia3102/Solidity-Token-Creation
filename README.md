# My_TokeN Solidity Smart Contract

This Solidity smart contract represents a basic token contract with minting and burning capabilities. It can be used as a starting point for creating your own custom tokens on the Ethereum blockchain.

## Contract Details

- *Contract Name:* My_TokeN
- *Version:* 0.8.18
- *License:* MIT License

## Public Variables

- tok_nAME: The name of the token (Example: "Sourin").
- _tok_abbr: The abbreviation of the token (Example: "S").
- total_supply: The total supply of the token (initialized to 0).

## Mapping

- balance: A mapping that associates addresses with their token balances. Users can check their token balances using this mapping.

## Mint Function

The mint function allows users to increase the total token supply by minting new tokens and assigning them to a specific address.

*Parameters:*
- Addr: The address to which the minted tokens will be assigned.
- Value: The number of tokens to mint.

## Burn Function

The burn function allows users to decrease the total token supply by burning (destroying) tokens from a specific address.

*Parameters:*
- Addr: The address from which tokens will be burned.
- Value: The number of tokens to burn.
