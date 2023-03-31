# Technical Details

OMoD is built on the C4Chain private network, which is a permissioned blockchain that enables secure, efficient, and decentralized storage of medical data. The network uses a consensus mechanism based on Proof of Stake (PoS), which ensures the security and scalability of the network. The medical data is stored on the C4Chain network using the IPFS protocol, which enables efficient and decentralized storage of large amounts of data. The metadata of the medical data is stored on the Filecoin network, which provides secure and efficient storage of metadata using a Proof of Replication (PoRep) consensus mechanism. The metadata contains the necessary information to access the medical data stored on the IPFS network, such as the file hash and decryption keys.

OMoD leverages the security and scalability of Polygon Edge, a Layer 2 scaling solution for Ethereum, to enable efficient and secure storage and management of medical data. Polygon Edge provides fast and low-cost transactions, interoperability with other Ethereum-based chains, and compatibility with the Ethereum Virtual Machine (EVM). OMoD utilizes the Polygon Bridge to enable seamless transfer of medical data between the C4Chain network and other Ethereum-based networks.

OMoD provides patients with complete control over their medical records by enabling them to choose who can access their data and when. Patients can authorize access to their medical records using a secure blockchain-based ID verification solution like Sovrin. Once authorized, medical professionals can access the patient's records and provide personalized healthcare services. OMoD also provides pregnant women with smart notifications, alerting them to important milestones and appointments. The application can also notify doulas and midwives of incoming births, ensuring that the birthing process is as smooth as possible.

To illustrate how the app will interact with other chains, medical professionals, and patients, below is a flowchart:

```
           +-------------------+
           |   Medical Chain   |
           +---------+---------+
                     |
                     |
           +---------v---------+
           |   C4Chain Network |
           +---------+---------+
                     |
                     |
           +---------v---------+
           |   Polygon Edge    |
           +---------+---------+
                     |
                     |
    +----------------+----------------+
    |                                 |
+---v---+                         +---v---+
|  NFT  |                         |  NFT  |
+---+---+                         +---+---+
    |                                 |
    |                                 |
+---v---+                         +---v---+
|Patient|                         |Doctor |
+-------+                         +-------+

```

As shown in the flowchart, medical data is stored on the C4Chain network, which interacts with Polygon Edge for an added layer of data security. NFTs can be transferred to and from other EVM-based chains through the bridge. Patients can access and control their medical data through the app, and doctors can access the data with the patient's consent.
