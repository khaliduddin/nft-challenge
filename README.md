# NFT minting with Python & Solidity

## Mint ERC721 token to any EVM compatible chain

### This project is implemented using Python and uses Brownie framework to support Solidity smart contract programming. 

#### This smart contract developed in Nftbrownie.sol is a basic implementation to mint an ERC721 token to any Ethereum [EVM] compatible blockchain.
#### Brownie is a Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.

### Steps to run the code:

- Create .env file with Keys in below format:
    <br>PRIVATE_KEY = 0x<Copy private key of your WALLET Address>
    <br>WEB3_INFURA_PROJECT_ID = <Copy Project ID from Infura Testnet of your choice. Provide the network name in brownie-config.yaml>
- Change path to Project root directory and Run below command to install brownie
    <br>pip install brownie
- Once brownie is successfully installed, run below command to install dependency packages and compile Solidity .sol files
- Deploy the smart contract using the scripts/deploy.py with following command. Specify the network of your choice in place of rinkeby
    <br>brownie run scripts/deploy.py --network rinkeby
- Mint NFT using the scripts/mintnft.py with following command. Specify the network of your choice in place of rinkeby
    <br>brownie run scripts/mintnft.py --network rinkeby
    <br><small>Note: Provide any image of your choice from IPFS. I have provided a sample image URI from Pinata already for public usage.</small>
  
##### Details of Developer/Team: 
  - <a href="https://github.com/khaliduddin">khalid</a>
 
