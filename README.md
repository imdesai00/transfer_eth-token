# Transfer Ether from one account to other

Tranfer ETH from one account to other using web3.js and Ganache

## Project Setup

1. Install node.js
2. Install ganache 
3. Create react app project `npx create-react-app 02_ethtransfer`
4. Update package.json with provided libraries
5. Run `npm install`

### Code 

1. Setup variables into .env file
2. Read variables from .env file
3. Connect to the ganache blockchain using web3
4. Write transfer function (refer `main.component.js`) 

### .env
you need to create one file in your root directory name that(.env) that file contain information about the account
REACT_APP_ACCOUNT=Account's Address
REACT_APP_PRIVATE_KEY=Account's Private Key

REACT_APP_RPC_HTTP_URL=HTTP://127.0.0.1:7545
