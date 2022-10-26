# Fundamentals

Learn about basic fundamentals of blockchain architecture.

## What is blockchain?

* Blockchain is a linked list of data. The data can be considered as blocks which contains - Block Header and Block Body.
* Block header contains the calculated hash of the entire data of the block
* Block body contains the Merkle Root which contains list of all transactions that are hashed

![Fundamentals-1](https://github.com/Verseium/web3-architecture/blob/main/Diagrams/Fundamentals-1.drawio.png)


## Key Features

1. All the data is ** cryptographically hashed ** using public private key infrastructure.
2. Every Block is ** time-stamped and chronologically linked **.
3. The data is ** immutable **.
4. Merkle Roots and Previous hash can be used to search the data in any block.
5. Blockchain is peer to peer network where computer/devices having the right software can interact with each other.
