# 🏧 Bank

Your wallet is used for wagers and purchases. The bank keeps credits separate from your immediately spendable balance.

| Command | Purpose | Example |
| --- | --- | --- |
| `/balance` | Show your wallet and bank totals | `/balance` |
| `/bank balance` | Open the detailed bank view | `/bank balance` |
| `/bank deposit <amount>` | Move wallet credits into the bank | `/bank deposit 5000` |
| `/bank withdraw <amount>` | Move bank credits back to your wallet | `/bank withdraw 2500` |
| `/pay <user> <amount>` | Send credits to another player | `/pay @Player 1000` |

Amounts must be positive whole numbers. A wager or shop purchase uses wallet credits, so withdraw first if the credits are stored in your bank.
