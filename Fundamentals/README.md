# Fundamentals

Learn about basic fundamentals of blockchain architecture.

## What is blockchain?

* Blockchain is a linked list of data. The data can be considered as blocks which contains - Block Header and Block Body.
* Block header contains the calculated hash of the entire data of the block
* Block body contains the Merkle Root which contains list of all transactions that are hashed

![Fundamentals-1](https://github.com/Verseium/web3-architecture/blob/main/Diagrams/Fundamentals-1.drawio.png)


## Key Features

1. All the data is **cryptographically hashed** using public private key infrastructure.
2. Every Block is **time-stamped and chronologically linked**.
3. The data is **immutable**.
4. **Merkle Roots** and Previous hash can be used to search the data in any block.
5. Blockchain is **peer to peer network** where computer/devices having the right software can interact with each other.
6. The blockchain is **distributed** which means that every device participating in the network will synchronously have the same data.

## Interesting Facts

1. All the devices which participate in the blockchain are called **Nodes**.
2. Nodes that have blockchain software installed and running which facilitates computing power to the users are called **Clients**.
3. Clients having full blockchain data are called **Full Nodes**.
4. Clients having partial blockchain data are called **Partial/Light Nodes**.
5. Clients that have the capability to search and provide information required for external users are called **Service Providers**.
6. Devices that use a frontend software but donot run blockchain software are simply called **Dapps**.
7. All nodes combined is called as a **Network**.
8. Network with real life transactions is called **Mainnet**.
9. Networks with test transactions and dummy data for testing and experimentation are called **TestNets**.


## Public-Private key

Asymmetric Cryptographic algorithms like SHA256 or ECDSA algorithms are used to generate the keys.

![Fundamentals-2](https://github.com/Verseium/web3-architecture/blob/main/Diagrams/Fundamentals-2.drawio.png)

## Transactions

1. Txns are just records of data in chronological order that are hashed.
2. Txns are stored in a merkle tree
3. All the txns are collected and stored in a Transaction pool/Memorypool.
4. This pool is added to the blockchain by the miners.

![Fundamentals-3](https://github.com/Verseium/web3-architecture/blob/main/Diagrams/Fundamentals-3.drawio.png)

## Wallets

### Determenistic wallets

1. Heirarchial determenestic is a type of wallet(app) which is generated from a seed phrase.
2. This seed phrase can generate child keys from parent key which means that one seed can genearte infinte public and private key pairs.
3. The BIP 32 Protocol is the tech behind these generation.


### Mnemonic Wallets



## Smart Contracts



## Blockchain Alogorithms and cryptography

### ECDSA(Elliptic Curve Digital Signature Algorithm)



