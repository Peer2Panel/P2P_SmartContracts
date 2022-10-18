# P2P Smart Contracts
Smart contracts of the P2P ecosystem (NFT, marketplace, collateralized loans and stable coin).
All contracts are upgradables and allow for gassless transactions

- SolarT: Minting, Burning and handling all SolarT NFT informations
- MarketPlace: 

## Run contract test test
To compile and test the contracts (nodejs and hardhat), you need the following libraries:
- npm install hardhat
- npm install @nomiclabs/hardhat-ethers
- npm install @nomiclabs/hardhat-etherscan          
//to fetch data from etherscan
- npm install @openzeppelin/contracts
- npm install @openzeppelin/hardhat-upgrades        
//for deployement of upgradable contracts
- npm install @openzeppelin/contracts-upgradeable   
//for upgradable contracts
- npm install @opengsn/contracts@2.2.6              
//for gassless meta-transactions
- npm install hardhat-contract-sizer                
//If you wanna track the size of your contract (max size is 24KiB on EVM)

Then, you can run the test with
- npx hardhat run scripts/run_test.js

## SolarT value
Our marketplace use a deterministic function to determine the panels value

