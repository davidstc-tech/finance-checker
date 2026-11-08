# Finance Checker

Finance Checker is a personal dashboard app. It runs only on my own computer
and connects only my own accounts. It has no other users.

## What it does
- Shows my account balances, monthly spending by category, and recent transactions
  (bank data through Plaid).
- Shows my sleep and calories burned from my own Oura Ring (through the Oura API).

## Privacy
- Data is used only to show me my own finances and health. It is never sold or shared.
- Bank data, Plaid access tokens, and Oura health data are stored only on my computer,
  which uses full-disk encryption. Oura sign-in tokens are kept in the macOS Keychain.
- Health data from Oura is only displayed to me. It is not sent to any other service,
  including AI services.
- The app does not run on any public server and cannot be reached from the internet.
- Disconnecting a bank in the app removes it from Plaid and deletes its data
  from my computer. Disconnecting Oura in the app deletes its sign-in tokens.

## Terms
- This app is for my personal use only. It is not offered to anyone else, and no one
  else can sign up for it or connect their accounts.
- It is provided as is, with no warranty. It only reads my own data from Plaid and
  Oura to show it to me.

Contact: <tdavidson240@gmail.com>
