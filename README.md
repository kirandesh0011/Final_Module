# CakePurchase 

## Overview

The CakePurchase smart contract facilitates the purchase of cakes using a custom cryptocurrency called CakeCoin (CCC). Users can buy cakes of different flavors by spending CakeCoin tokens.

## Features

- **Cake Flavors**: Offers three flavors of cakes: Vanilla, Chocolate, and Strawberry.
- **Token Management**: Manages the creation, transfer, and burning of CakeCoin tokens.
- **Ownership**: Grants special privileges to the contract owner, such as minting new tokens.
- **Event Logging**: Logs events whenever a cake is purchased, ensuring transparency in transactions.

## Functions

1. **Constructor**: Initializes the contract with an owner address and sets up the token details.
2. **Mint Tokens**: Enables the contract owner to create new CakeCoin tokens and assign them to specific addresses.
3. **Burn Tokens**: Allows users to destroy their CakeCoin tokens, reducing the total supply.
4. **Purchase Cake**: Lets users buy cakes using CakeCoin tokens. Deducts the appropriate token amount from the user's balance and records the purchased cake flavor.
5. **Transfer Cake Tokens**: Allows users to transfer CakeCoin tokens to other addresses.

## Usage

1. Deploy the smart contract, specifying the initial owner address.
2. Mint CakeCoin tokens to distribute among users or facilitate cake purchases.
3. Users interact with the contract by purchasing cakes or transferring tokens.
4. The contract owner manages the token supply by minting or burning tokens as necessary.

## License

This software is licensed under the MIT License.

