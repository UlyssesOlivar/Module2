# DESCRIPTION
A specialized tool known as "avalanche" lets users build blockchain networks and construct and run apps without the need for middlemen. The purpose of avalanche is to address the problems of throughput and scalability that plague conventional blockchain systems. The Avalanche consensus protocol powers the platform's incredibly quick transactions and millisecond finality. Because of Avalanche's layered architecture, which can adjust to scalability issues, developers can create blockchain networks with the features that best suit their needs and the use cases at hand.

This project links users' MetaMask wallets to the project, allowing them to check their account balance, deposit and receive money, multiply the amount by two among other features—all while creating a basic FRAUD DETECTION SYSTEM using React and Ethereum blockchain technologies.

# INITIAL STEPS
1. Connect Metamask Wallet to the ATM
2. View Account Balance
3. Deposit and Withdraw funds
4. Multiply the value by 2

# INSTALLATION
1. Add the Metamask wallet to your web browser.
2. Two more terminals should be opened in your VS code.
3. npx hardhat node is the terminal type used in the second.
4. Enter: npx hardhat run --network localhost scripts/deploy.js in the third terminal.
5. To open the front-end, return to the first terminal and do npm run dev.
6. The project will be running on your localhost when you open the application in your browser. At: http://localhost:3000, usually
7. Open the ATM interface and connect your MetaMask wallet.

# SET METAMASK UP TO UTILIZE THE HARDHAT NODE.
1. In your browser, open the MetaMask extension.
2. Choose "Settings" after clicking the account icon in the upper right corner.
3. Click "Add Network" under the "Networks" tab.
4. Complete the following fields:
5. Yuli's as Network Name
6. http://127.0.0.1:8545 is the RPC URL.
7. ID of Chain: 31337
8. ETH as currency symbol
9. Select "Save" in order to incorporate the Hardhat network into MetaMask.

# HARDHAT CREATES ACCOUNTS USING PRIVATE KEYS FOR TESTING
1. Click on the account icon in the upper right corner of the MetaMask extension.
2. Choose "Import Account" or "Import Account with Private Key" based on the MetaMask version you are using.
3. Enter one of the private keys that Hardhat has provided in the "Private Key" field.
4. Open the terminal where you launched the Hardhat local network to see the list of private keys.
5. The accounts created by Hardhat include the private keys presented.
6. To import the account into MetaMask, click "Import".
7. To add extra accounts for testing, use the previously mentioned procedures.

# USAGE
To utilize the application, comply to these guidelines:

1. Once MetaMask is connected to the Hardhat local network, link the program to your wallet.
2. Enter the recipient's address and the desired transfer amount after clicking on Transfer Funds.
3. To start the transaction, click the "Transfer" button.
4. In MetaMask, confirm the transaction.
5. The account balance will be changed and the transaction information will be recorded on the console.

# Author
Olivar, Ulysses O.

3.1 BSIT
