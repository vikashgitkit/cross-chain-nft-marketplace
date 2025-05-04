# MetaBazaar

MetaBazaar is a feature-rich NFT marketplace built to provide a seamless and engaging experience for NFT enthusiasts. The platform offers robust features including NFT minting, a marketplace with search functionality, and user profiles. It also integrates with MetaMask for wallet connectivity and utilizes IPFS for image storage.

## Tech Stack

![Solidity](https://img.shields.io/badge/Solidity-%23000000?style=for-the-badge&logo=solidity&logoColor=white)  
![Hardhat](https://img.shields.io/badge/Hardhat-%23202333?style=for-the-badge&logo=hardhat&logoColor=white)  
![Ethereum](https://img.shields.io/badge/Ethereum-%23000000?style=for-the-badge&logo=ethereum&logoColor=white)  
![Alchemy](https://img.shields.io/badge/Alchemy-%2300B1E1?style=for-the-badge&logo=alchemy&logoColor=white)  
![Next.js](https://img.shields.io/badge/Next.js-%23000000?style=for-the-badge&logo=next.js&logoColor=white)  
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)  
![Accertainty UI](https://img.shields.io/badge/Accertainty%20UI-%23F3F4F6?style=for-the-badge&logoColor=black)  
![MetaMask](https://img.shields.io/badge/MetaMask-%23F6851B?style=for-the-badge&logo=metamask&logoColor=white)  
![Pinata](https://img.shields.io/badge/Pinata-%23F6C343?style=for-the-badge&logo=pinata&logoColor=white)  

## Features

- **Wallet Connect**: Connect your wallet using MetaMask.
- **NFT Minting**: Create and mint your own NFTs.
- **Marketplace**: Browse and search for NFTs.
- **User Profiles**: View owned NFTs and transaction history.
- **Search Functionality**: Efficiently search for NFTs in the marketplace.
- **Image Storage**: Images are stored on IPFS via Pinata.

## How to install and run

1. Clone the repository
   ```
   git clone https://gitlab.com/flutchidev/cross-chain-marketplace.git
   ```
2. Install dependencies and Run the app
   ```
   cd ./cross-chain-marketplace/frontend
   npm install
   npm run dev
   ```
## How to start localtest network and deploy contract

1. Start the local test node
   ```
   npx hardhat node
   ```
2. Deploy the contract
   ```
   npx hardhat run scripts/deploy.js --network localhost
   ```
3. Run the app
   ```
   cd frontend
   npm install
   npm run dev
   ```
