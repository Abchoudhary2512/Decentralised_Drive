## Decentralized Drive

### Overview
Our project aims to develop a decentralized alternative to traditional cloud storage services like Google Drive. By leveraging blockchain technology, we prioritize data control, privacy, and security while providing efficient file sharing capabilities.

### Technologies Used

- **Frontend Development with React.js**: We utilize React.js to create an intuitive user interface, enabling users to interact with the application seamlessly.
- **Smart Contract Development with Hardhat**: Hardhat is utilized as our Ethereum development environment for constructing resilient smart contracts that govern storage and access control logic. These smart contracts are authored in Solidity.
- **Interacting with Ethereum using Ether.js**: Ether.js simplifies communication with the Ethereum blockchain, facilitating various operations such as file uploading, access control, and file sharing.
- **IPFS**: For storing data in decentralized manner.
### Features 
- **User Registration and Authentication:**
  - Secure account creation and authentication enabled through blockchain technology for transparency and immutability.
  
- **Decentralized Storage:**
  - Utilization of decentralized storage system distributes user files across multiple network nodes, reducing single points of failure and enhancing data availability.

- **Data Control and Privacy:**
  - Complete user control over data ensured with cryptographic techniques for privacy and security.
  - Smart contracts govern access control, allowing users to define permissions and selectively share files.

- **Data Integrity and Security:**
  - Blockchain ensures data integrity and security by storing cryptographic hashes of uploaded files, enabling verification and preventing tampering.

- **Efficient File Sharing:**
  - Streamlined file sharing directly between users facilitated by smart contracts managing access permissions.

- **Cost-Effectiveness:**
  - Blockchain technology reduces costs associated with centralized cloud storage by allowing users to contribute unused storage resources and earn incentives or pay only for utilized storage.





## Hardhat Commands
Try running some of the following tasks:
```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```
