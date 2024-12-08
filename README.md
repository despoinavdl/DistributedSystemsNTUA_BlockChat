# BlockChat - Proof of Stake Cryptocurrency Implementation

This repository contains a **Proof of Stake (PoS)** cryptocurrency implementation built using Python. It demonstrates the core concepts of blockchain technology, such as **transaction validation**, **block minting**, **Proof of Stake consensus**, and **distributed network communication**.

The project allows for the creation and validation of transactions and blocks, with nodes in the network participating based on their stake. It implements a decentralized system where each node has a wallet, a transaction pool, and a blockchain that is validated according to the PoS protocol.

### **Authors**
- **Ioannis Dorkofikis**
- **Despoina Vidali**

# Proof of Stake Cryptocurrency

This is an implementation of a **Proof of Stake (PoS)** cryptocurrency system where nodes can create transactions, validate blocks, and mine new coins based on the amount of stake they have. It supports multiple nodes, each with its own wallet and balance, and ensures secure and validated transactions via digital signatures and Proof of Stake consensus.

## Key Features:
- **Proof of Stake Consensus**: Nodes validate blocks based on their stake, and the miner is chosen randomly based on the stakes in the network.
- **Transaction Fees**: Nodes pay a small fee when creating a transaction. The fee is deducted from the sender's balance and is rewarded to the miner who successfully mines the block containing the transaction.
- **Blockchain**: A secure, immutable blockchain that records all transactions.
- **Wallet**: Each node has its own wallet, which stores the public and private keys and tracks balances.
- **Network Communication**: Nodes communicate over HTTP to send transactions, register new nodes, and propagate blocks.

## How It Works

### Transaction Creation
- **Transaction Fees**: When a node creates a transaction, a small transaction fee is deducted from the sender's balance. The fee is paid to the miner who successfully validates the block containing the transaction.
  
### Proof of Stake
- Nodes with more coins (higher stake) have a greater chance of being selected as the validator (miner) of the next block, which ensures a decentralized and secure network without requiring significant computational resources.
  
### Node Registration
- New nodes join the network by registering with a bootstrap node. Once verified, they are added to the list of active nodes, with an initial stake that influences their chances of validating blocks.

