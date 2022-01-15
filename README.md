# nft-token-sample

### Overview
Here is a summary of the steps to be taken to build our token:

 1. Initialize a project using Truffle;
 2. Install Open Zeppelin smart contracts in the project folder;
 3. Create a wallet mnemonic;
 4. Configure Truffle to connect to RSK testnet;
 5. Get some tRBTC from a faucet;
 6. Create smart contract of token;
 7. Create deploy file at Truffle;
 8. Deploy a smart contract on RSK Testnet using Truffle;
 9. Interact with the smart contract at Truffle console.

### Requirements
Node.js and NPM (Node Package Manager)
Visual Studio Code (VSCode) or any other editor of your choice
Truffle


The result value is presented in hexadecimal. 0xc3f9b is the block number in hexadecimal, the corresponding decimal is: 802715. To verify the block number, visit explorer.testnet.rsk.co.
0xb774Aa2876145b2f6F3DE27E5E6Ac970aa12d771

![Screen Shot 2022-01-16 at 12 44 57 AM](https://user-images.githubusercontent.com/11626327/149628161-fd597611-33b3-4595-bc47-8830e84e6e86.png)




### Create a mnemonic
just clicl : https://iancoleman.io/bip39/#english

    The way we are creating the mnemonic is not recommended to be used for any ‘real’ wallet because it’s not secure generate a private key in a website, however we will use this here for learning purposes, and since we’re using the Testnet anyway.
    
  ![Screen Shot 2022-01-16 at 12 44 45 AM](https://user-images.githubusercontent.com/11626327/149628077-0d1643c6-87e6-4418-9bba-30a71b0733b0.png)




### Testnet Faucet
You can get some tRBTC from the RSK Testnet faucet.

0x948f286fd4122e4c02247e6e0908a2f7ae6399b6

![Screen Shot 2022-01-16 at 12 43 49 AM](https://user-images.githubusercontent.com/11626327/149628103-74aacf33-8e2e-4278-a751-2cde87dae003.png)

Deploy a smart contract
First of all, we need to create a a new migrations file where Truffle will find it, containing instructions to deploy the smart contract.


### Create token deployment file
The migrations folder has JavaScript files that help you deploy contracts to the network.
These files are responsible for staging your deployment tasks, and they’re written under the assumption that your deployment needs will change over time. 
A history of previously run migrations is recorded on-chain through a special Migrations contract. 
(source: truffle: running-migrations)
