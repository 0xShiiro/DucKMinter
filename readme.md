# Duckminter

Duckminter is a decentralized application (DApp) that allows users to mint Non-Fungible Tokens (NFTs) on the Polygon Amoy network. The application leverages the Starton API and IPFS (InterPlanetary File System) to create and store NFTs, providing a seamless experience for users to mint, manage, and view their NFTs.

## Features

- **Mint NFTs**: Users can mint unique NFTs, which are securely stored on IPFS.
- **View Minted NFTs**: Users can view their previously minted NFTs directly through the DApp.
- **Polygon Amoy Network**: All NFTs are minted on the Polygon Amoy network, ensuring fast and cost-effective transactions.

## Technologies Used

- **Starton API**: Facilitates the interaction between the DApp and the blockchain network.
- **IPFS**: Used for decentralized storage of NFTs.
- **Polygon Amoy**: The network on which NFTs are minted, chosen for its scalability and low transaction fees.

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later)
- A wallet that supports Polygon (e.g., MetaMask)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/duckminter.git
   cd duckminter
   ```
   
2. Install the required dependencies:

```bash
npm install
```
  
3. Start the development server:

```bash
npm start
```

### Usage
-Connect your wallet to the DApp.
-Choose the image or artwork you want to mint as an NFT.
-Provide a name and description for your NFT.
-Click "Mint" to create your NFT. The NFT will be stored on IPFS, and a transaction will be initiated on the Polygon Amoy network.
-View your minted NFTs on the "My NFTs" page.

### Enviroment Variables
STARTON_API_KEY=your-starton-api-key
