# STEWRY

**STEWRY** is a Web3 storytelling and monetization platform that empowers users to write, share, and monetize stories on the blockchain. Built on the Flow blockchain, STEWRY enables authors to retain ownership of their work while offering readers the option to support and unlock full stories through tipping.

## Features
- **Blockchain-Based Story Publishing**: Allows authors to upload stories to the blockchain, ensuring security and ownership.
- **Monetization Through Tipping**: Readers can read a story preview, then tip the author to unlock the full content.
- **Wallet Integration**: Easily connect a wallet to publish stories or tip authors.
- **EVM-Compatible**: Supports Ethereum-based features and works seamlessly with EVM-compatible networks.

## Tech Stack
- **Frontend**: React with Vite for optimized performance
- **Blockchain**: Flow Blockchain, with smart contracts written in Solidity
- **Smart Contract**: `Stewry.sol` - manages story storage, access, and tipping functionality

## Project Structure
```plaintext
📁 src
 ├── 📁 components
 │    ├── Navbar.jsx         # Navigation bar with wallet connection
 │    ├── StoryPreview.jsx   # Displays preview of each story
 │    ├── TipButton.jsx      # Tipping functionality for readers
 │    └── StoryUpload.jsx    # Upload page for authors
 ├── 📁 contracts
 │    └── Stewry.sol         # Smart contract for story storage and tipping
 ├── App.js                  # Main app component
 └── config.json             # Contract addresses and configuration

Setup and Installation
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/stewry.git
cd stewry
Install Dependencies

bash
Copy code
npm install
Environment Setup

Configure your config.json file with contract addresses and network information.
Start the Development Server

bash
Copy code
npm run dev
Usage
Connect Wallet: Connect your wallet through the Navbar to enable story uploads and tipping.
Upload Story: Use the StoryUpload page to write and publish a story. The story will be stored on the Flow blockchain.
Read and Tip: Readers can view the first few lines of a story and tip the author to unlock the full content.
Smart Contract
Stewry.sol is the main smart contract for story publishing and monetization. Key functions include:

uploadStory: Allows authors to upload a new story with a preview and full content.
tipAuthor: Allows readers to send tokens to the story author, unlocking the full story for the reader.
Contributing
Feel free to open issues or submit pull requests to contribute to STEWRY. Make sure to follow the contribution guidelines in CONTRIBUTING.md.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or support, reach out at [Your Email] or open an issue in the repository.
