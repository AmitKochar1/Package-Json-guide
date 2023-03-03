*** Universal Json file to Install all the packages at one place ***

1. To install npx hardhat

npm install --save-dev hardhat

2. hardhat deploy

npm install -D hardhat-deploy

hardhat.config file ----> require('hardhat-deploy');

npm install --save-dev  @nomiclabs/hardhat-ethers@npm:hardhat-deploy-ethers ethers

3. Gas-repoter

link - https://www.npmjs.com/package/hardhat-gas-reporter

npm install hardhat-gas-reporter --save-dev

hardhat.config file ----> require("hardhat-gas-reporter");

module.exports = {
  gasReporter: {
    currency: 'CHF',
    gasPrice: 21,
    enable: true,
  }
}

*** To continue ***