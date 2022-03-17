# Day 0: Welcome To Blockchain

## Table of Contents
- [Table of Contents](##table-of-contents)
- [What is a Blockchain?](##what-is-a-blockchain?)
- [Advantanges of Blockchain?](##advantanges-of-blockchain?)
- [How Do Blockchain Work?](##how-do-blockchain-work?)
- [Blockchain Oracles](##blockchain-oracles)
- [Consensus](##consensus)
- [Miscellaneous](##miscellaneous)


## What is a blockchain

A blockchain is a *distributed database* that is shared among the nodes of a computer network. As a database, a blockchain stores information electronically in digital format. Blockchains are best known for their crucial role in cryptocurrency systems, such as [Bitcoin](https://bitcoin.org/bitcoin.pdf), for maintaining a secure and decentralized record of transactions. The innovation with a blockchain is that it guarantees the *fidelity* and *security* of a record of data and generates trust **without** the need for a trusted third party.

One key difference between a typical database and a blockchain is how the data is structured. A database usually structures its data into tables, whereas a blockchain, like its name implies, structures its data into chunks (blocks) that are strung together. Blocks have certain storage capacities and, when filled, are closed and linked to the previously filled block, forming a chain of data known as the blockchain. All new information that follows that freshly added block is compiled into a newly formed block that will then also be added to the chain once filled. This data structure inherently makes an *irreversible* time line of data when implemented in a decentralized nature. When a block is filled, it is set in stone and becomes a part of this time line. Each block in the chain is given an exact time stamp when it is added to the chain.

**KEY TAKEAWAYS**
- Blockchain is a type of shared database that differs from a typical database in the way that it stores information; blockchains store data in blocks that are then linked together via cryptography.
- As new data comes in, it is entered into a fresh block. Once the block is filled with data, it is chained onto the previous block, which makes the data chained together in chronological order.
- Different types of information can be stored on a blockchain, but the most common use so far has been as a ledger for transactions.
- In Bitcoin’s case, blockchain is used in a decentralized way so that no single person or group has control—rather, all users collectively retain control.
- Decentralized blockchains are immutable, which means that the data entered is irreversible. For Bitcoin, this means that transactions are permanently recorded and viewable to anyone.

## Advantanges of Blockchain?

The goal of blockchain is to allow digital information to be recorded and distributed, but not edited. In this way, a blockchain is the foundation for immutable ledgers, or records of transactions that cannot be altered, deleted, or destroyed.

A blockchain allows the data held in that database to be spread out among several network nodes at various locations. This not only creates redundancy but also maintains the fidelity of the data stored therein—if somebody tries to alter a record at one instance of the database, the other nodes would not be altered and thus would prevent a bad actor from doing so. If one user tampers with Bitcoin’s record of transactions, all other nodes would cross-reference each other and easily pinpoint the node with the incorrect information. This system helps to establish an exact and transparent order of events. This way, no single node within the network can alter information held within it. Because of this, the information and history (such as of transactions of a cryptocurrency) are irreversible.

#### Transparency
Because of the decentralized nature of Bitcoin’s blockchain, all transactions can be transparently viewed by either having a personal node or using blockchain explorers that allow anyone to see transactions occurring live. Each node has its own copy of the chain that gets updated as fresh blocks are confirmed and added. This means that if you wanted to, you could track Bitcoin wherever it goes.

Of course, the records stored in the Bitcoin blockchain (as well as most others) are encrypted. This means that only the owner of a record can decrypt it to reveal their identity (using a public-private key pair). As a result, users of blockchains can remain anonymous while preserving transparency.

#### Security
Blockchain technology achieves decentralized security and trust in several ways. To begin with, new blocks are always stored linearly and chronologically. That is, they are always added to the “end” of the blockchain. After a block has been added to the end of the blockchain, it is extremely difficult to go back and alter the contents of the block unless a majority of the network has reached a consensus to do so. That’s because each block contains its own hash, along with the hash of the block before it, as well as the previously mentioned time stamp. Hash codes are created by a mathematical function that turns digital information into a string of numbers and letters. If that information is edited in any way, then the hash code changes as well.

## How Do Blockchain Work?
- [Blockchain Demo](https://andersbrownworth.com/blockchain/)
- [Public / Private Keys](https://andersbrownworth.com/blockchain/public-private-keys/keys)
- [Layer 2 and Rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/)
- [Decentralized Blockchain Oracles](https://blog.chain.link/what-is-the-blockchain-oracle-problem/)
- [Block Rewards](https://www.investopedia.com/terms/b/block-reward.asp)
- [Run Your Own Ethereum Node](https://geth.ethereum.org/docs/getting-started)

## Blockchain Oracles
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)


## Consensus
In a blockchain, to validate new entries or records to a block, a majority of the decentralized network’s computing power would need to agree to it. To prevent bad actors from validating bad transactions or double spends, blockchains are secured by a consensus mechanism such as proof of work ([PoW](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)) or proof of stake ([PoS](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)). These mechanisms allow for agreement even when no single node is in charge.

- [Consensus](https://wiki.polkadot.network/docs/learn-consensus)
- [Nakamoto Consensus](https://blockonomi.com/nakamoto-consensus/)

## Miscellaneous
- [What is a blockchain](https://www.investopedia.com/terms/b/blockchain.asp)
- [Blockchain Demo](https://andersbrownworth.com/blockchain/)
- [Public / Private Keys](https://andersbrownworth.com/blockchain/public-private-keys/keys)
- [Layer 2 and Rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/)
- [Decentralized Blockchain Oracles](https://blog.chain.link/what-is-the-blockchain-oracle-problem/)
- [Block Rewards](https://www.investopedia.com/terms/b/block-reward.asp)
- [Run Your Own Ethereum Node](https://geth.ethereum.org/docs/getting-started)
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)
- [DAOs](https://www.investopedia.com/tech/what-dao/)