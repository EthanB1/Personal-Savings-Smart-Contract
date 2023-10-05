# JointSavings Smart Contract

## Overview

The `JointSavings` smart contract facilitates the creation of a joint savings account that can be controlled by two users. This contract allows two users to deposit, withdraw, and manage a shared fund on the Ethereum blockchain.

## Features

- **Set Accounts**: 
  - Ability to specify two users who will control the joint savings account.
  
- **Deposit**: 
  - Any user can deposit funds into the joint account.
  
- **Withdraw**: 
  - Only the specified users can withdraw from the account, ensuring security.

- **Transaction Logs**: 
  - Tracks the user who made the last withdrawal and the amount, ensuring transparency.

## Usage

1. **Setting Up the Joint Account**: 
   - Call the `setAccounts` function with two payable addresses.

2. **Deposit Funds**: 
   - Send Ether to the contract address or use the `deposit` function to add funds to the joint account.

3. **Withdraw Funds**: 
   - If you're one of the joint account holders, call the `withdraw` function specifying the amount and your address.

## Notes

- Always ensure adequate funds before initiating a withdrawal.
  
- For security, only the two specified account holders can withdraw funds.

## Documentation

Screenshots of the contract transactions have been documented and can be found in the `execution_results` folder.
