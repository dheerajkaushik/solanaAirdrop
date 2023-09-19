# Solana Air Drop


This project is a simple web application that allows you to connect to a Solana wallet (e.g., Phantom Wallet) and airdrop SOL tokens to a specified account address. 
It uses the Solana Web3.js library for blockchain interaction.

## Project Overview

- Connect Wallet: Click the "Connect" button to connect to your Solana wallet(extension).

- Send : Enter the amount of SOL tokens you want to airdop in the input field and click on "Send" button.
- Disconnect: click on this button to disconnect your wallet.

## Getting Started

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/dheerajkaushik/solanaAirdrop.git
   ```

2. deploy the `index.html` file in a web browser.

## Usage

### Connect Wallet

1. Click the "Connect" button to connect to your Solana wallet


### Send SOL

1. Enter the amount of SOL you want to send in the input field labeled "Sol to send."

2. Click the "Send" button airdrop

3. You will see a status message indicating the transaction's progress.

4. The transaction will be confirmed on the Solana blockchain.



## Dependencies

- [Solana Web3.js](https://github.com/solana-labs/solana-web3.js): The Solana Web3.js library is used for interacting with the Solana blockchain.

## Notes

- This is a simplified example for educational purposes and may not cover all security and error-handling considerations for a production application.

- The project assumes you have a Solana wallet extension (e.g., Phantom Wallet) installed in your browser.

- Make sure to use a Solana development network (e.g., Devnet) for testing, as sending real SOL tokens on the mainnet can result in financial loss.


1.This command is used to generate a new Solana key pair (consisting of a public key and a secret key) and save it to a JSON file.
 ```bash
solana-keygen new 
```
2.This command is used to set the Solana cluster URL to the Devnet cluster.
 ```bash
solana config set --url https://api.devnet.solana.com
```
3.This command is used to request an airdrop of 1 SOL (Solana's native token) to a specified public key on the Solana blockchain.
 ```bash
solana airdrop 1 <Public Key>
```
4.This command is used to check the SOL token balance associated with the currently configured wallet.
 ```bash
solana balance
```

## author

Dheeraj

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
