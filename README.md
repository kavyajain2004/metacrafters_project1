# MyToken - Solidity Token Contract

## Description

MyToken is a simple Solidity smart contract that represents a basic token system. It includes functionalities for minting new tokens and burning existing ones. The contract adheres to specific requirements, such as storing token details (name, abbreviation, total supply), maintaining a balance mapping, and implementing mint and burn functions.


## Getting Started

1. **Token Details**: The contract has public variables (`tokenName`, `tokenAbbrv`, `totalSupply`) to store information about the token.

2. **Balances Mapping**: Utilizes a mapping (`balances`) to keep track of token balances for different addresses.

3. **Mint Function**: Provides a `mint` function that takes an address and a value as parameters, increasing the total supply by the specified amount and adding the same value to the balance of the sender's address.

4. **Burn Function**: Implements a `burn` function that, opposite to minting, destroys tokens. It deducts the specified value from the total supply and the sender's balance, but includes conditionals to ensure the sender's balance is sufficient for burning.

## License
This project is licensed under the MIT License
