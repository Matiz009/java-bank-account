# Java Bank Account

A Java console program that simulates a bank account.

## Features

- Shows the account holder and current balance
- Deposit an amount
- Withdraw an amount
- View the balance
- Exit from the menu

> **Known issue (TODO):** a new `BankAccount` is created on every pass through the menu loop, so the balance goes back to its starting value after each action. Withdrawals also don't check that the balance is high enough.

## Tech stack

Java

## Getting started

```bash
git clone https://github.com/Matiz009/java-bank-account.git
cd java-bank-account
javac BankAccount.java BankAccountTest.java
java BankAccountTest
```

## Project structure

```
BankAccount.java       Account class (deposit, withdraw)
BankAccountTest.java   Console menu
*.class                Old compiled builds
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
