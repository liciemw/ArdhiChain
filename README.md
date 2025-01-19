# ArdhiChain: Decentralized Land Ownership Management on Ethereum    

## Overview  
ArdhiCain is a decentralized application (dApp) that uses the Ethereum blockchain to provide secure, transparent, and tamper-proof land ownership management. Designed to address land ownership challenges in rural communities, it ensures equitable, verifiable, and accessible records for property transactions.  

## Key Features

- **Decentralized Land Registry:** Immutable and tamper-proof land records stored on the Ethereum blockchain.
- **Mobile Number Integration:** Combines Ethereum wallet addresses with mobile number verification for accessibility and trust.
- **Secure Ownership Transfers:** Automated smart contracts handle ownership changes with OTP-based verification.
- **User-Friendly Interface:** A React-based frontend ensures accessibility for users with smartphones and feature phones.
- **Decentralized Storage:** Large files, such as land maps and certificates, are stored securely on IPFS.

## How It Works

### Registration Process
1. **User Identification:** Users register with their mobile number, generating an Ethereum wallet address linked to their identity.
2. **Land Data Submission:** Users submit land details and ownership proof, verified by authorized personnel.
3. **Blockchain Entry:** Verified land information is recorded on a smart contract, creating an immutable ownership record.

### Ownership Transfers
1. **Initiation:** Owners initiate transfer requests using the recipient's mobile number or Ethereum wallet address.
2. **Verification:** OTP-based verification ensures genuine agreement from both parties.
3. **Smart Contract Execution:** Ownership records are updated on the blockchain, and the new owner's details are recorded.

### Accessibility
- **Mobile Devices:** Users can access land records via a mobile-friendly interface or SMS for feature phones.
- **Decentralized Storage:** Land maps and certificates are stored on IPFS, linked to the blockchain.

## Technical Stack
- **Blockchain:** Ethereum for decentralized and secure transactions.
- **Smart Contracts:** Developed in Solidity to handle land registration and transfers.
- **Frontend:** React-based interface for user interactions.
- **Storage:** IPFS for decentralized storage of large files.
- **Authentication:** Mobile number verification with OTP for enhanced security.

## Security Measures
1. **Mobile Number Verification:** Prevents unauthorized access to the platform.
2. **Encryption:** Ensures sensitive user data is protected during storage and transfer.
3. **Audited Smart Contracts:** All contracts are rigorously audited to prevent vulnerabilities.
4. **Role-Based Access:** Only authorized personnel can verify and modify land records.

## Getting Started

### Prerequisites
- Node.js and npm installed.
- Truffle and Ganache for Ethereum development.
- Metamask wallet for interacting with the dApp.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/liciemw/ArdhiChain.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ArdhiChain
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Deployment
1. Start a local blockchain using Ganache.
2. Compile and deploy the smart contracts:
   ```bash
   truffle migrate
   ```
3. Start the frontend:
   ```bash
   npm start
   ```

## Future Enhancements
- Integration with government land registries for official recognition.
- Support for multi-signature verification in high-value transactions.
- Expansion to other regions and use cases, including urban land management.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For more information or collaboration opportunities, please reach out at [alicemumbi82@gmail.com].

