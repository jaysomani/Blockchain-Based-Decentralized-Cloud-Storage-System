# Blockchain Based Decentralized Cloud Storage System

This project aims to build a decentralized cloud storage system that utilizes blockchain technology to provide secure and efficient storage for users. The system uses ReactJS for the front-end, Solidity for the smart contracts, EtherJS for blockchain interactions, and IPFS for decentralized file storage. The system will be hosted on Google Cloud and use AMD instances for improved performance.

Installation
To run this project locally, follow these steps:

Clone this repository: git clone https://github.com/jaysomani/Blockchain-Based-Decentralized-Cloud-Storage-System.git <br>
Install dependencies: npm install<br>
Deploy Contract: npx hardhat run scripts/deploy.js --network localhost
Start It: npx hardhat node
Start the development server: npm start

Usage
After starting the development server, you can access the application by navigating to http://localhost:3000 in your web browser. The application allows users to upload and download files securely, with all file data being stored on the IPFS network. Smart contracts are used to manage user authentication, file storage, and payment transactions.

License
This project is licensed under the MIT License - see the LICENSE file for details.
