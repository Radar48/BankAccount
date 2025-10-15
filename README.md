# BankAccount
A simple C# console banking application built for a Group Assignment . It allows users to create an account, deposit and withdraw funds, check their balance, view account summaries, and print statements. All sensitive actions are protected by a user-defined PIN. The project demonstrates core C# concepts. 
# Simple Banking Console App (C#)

This is a beginner-friendly C# console application. It simulates basic banking operations and demonstrates key programming concepts such as classes, methods, conditionals, and arrays.

## Features

- a bank account with:
  - Name
  - Account Number
  - PIN (used to secure sensitive actions)
- Deposit funds
- Withdraw funds
- Check account balance
- View account summary as an array:
  - Balance
  - Total Deposits
  - Total Withdrawals
- Print full account statement

## Security

- Users must enter their PIN to access balance, summary, or statement.
- If the PIN is incorrect, the user is logged out immediately.
- Deposits must be positive.
- Withdrawals cannot exceed the current balance.
