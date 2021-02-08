# Inbox

Simple inbox smart contract with mocha tests.

## Usage

#### Install modules
`npm install`

#### Mocha tests
`npm test`

#### Setup provider.js

Create provider file as follows, add your mnemonic and infura API.

```javascript
const HDWalletProvider = require('truffle-hdwallet-provider');

const provider = new HDWalletProvider(
  '[mnemonic phrase]',
  'https://rinkeby.infura.io/v3/ ... '
);

module.exports = provider;
```

#### Deploy to Rinkeby
`node deploy.js`
