# Poly_Module-1
Welcome to the inaugural project of Polygon Advance! In this module, our objective is to establish a seamless bridge between the Ethereum and Polygon blockchains, ultimately enabling the deployment and transfer of an NFT collection.

**Step 1: Crafting 5 Distinct NFTs**
To commence, we will create five unique NFTs. These digital assets will be uploaded onto the Pinata cloud storage platform.

**Step 2: Smart Contract Development**
A smart contract needs to be authored to manage the NFT collection. This contract will facilitate various functionalities like ownership and transfer. 

**Step 3: Script for Contract Deployment**
A script will be written to automate the contract deployment process. Execute the command "npx hardhat run scripts/deploy.js --network goerli" to initiate the deployment. Following the successful deployment, an address will be generated. Copy this address and update it within three files: contractAddress.js (in the metadata folder), batchMint.js (in the scripts folder), and approvedDeposit.js (within the nfts address).

**Step 4: Script for NFT Minting**
Utilize the script "npx hardhat run scripts/batchMint.js --network goerli" to execute the minting of the five NFTs. These NFTs will then be attributed to our designated address.

**Step 5: NFT Approval and Polygon Deposit**
To enable the seamless migration of our NFTs, execute the script "npx hardhat run scripts/approveDeposit.js --network goerli". This will initiate the approval and subsequent deposit of the minted NFTs from the Ethereum network to the Polygon Mumbai network through the FxPortal Bridge.

**Project Author**
Vishnu Vishvas Sharma

**Project License**
This project operates under the MIT License.

Feel free to reach out if you have any questions or need further assistance during this exciting journey of building with the Polygon Bridge.
