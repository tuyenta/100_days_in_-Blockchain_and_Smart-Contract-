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

A blockchain is a public database that is updated and shared across many computers in a network.

"Block" refers to data and state being stored in consecutive groups known as "blocks". If you send ETH to someone else, the transaction data needs to be added to a block to be successful.

"Chain" refers to the fact that each block cryptographically references its parent. In other words, blocks get chained together. The data in a block cannot change without changing all subsequent blocks, which would require the consensus of the entire network.

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

Blockchain consists of three important concepts: blocks, nodes and miners.

### Blocks
Every chain consists of multiple blocks and each block has three basic elements:

- The data in the block.
- A 32-bit whole number called a nonce. The nonce is randomly generated when a block is created, which then generates a block header hash.
- The hash is a 256-bit number wedded to the nonce. It must start with a huge number of zeroes (i.e., be extremely small).
When the first block of a chain is created, a nonce generates the cryptographic hash. The data in the block is considered signed and forever tied to the nonce and hash unless it is mined.
### Miners
Miners create new blocks on the chain through a process called mining.

In a blockchain every block has its own unique nonce and hash, but also references the hash of the previous block in the chain, so mining a block isn't easy, especially on large chains.

Miners use special software to solve the incredibly complex math problem of finding a nonce that generates an accepted hash. Because the nonce is only 32 bits and the hash is 256, there are roughly four billion possible nonce-hash combinations that must be mined before the right one is found. When that happens miners are said to have found the "golden nonce" and their block is added to the chain.

Making a change to any block earlier in the chain requires re-mining not just the block with the change, but all of the blocks that come after. This is why it's extremely difficult to manipulate blockchain technology. Think of it as "safety in math" since finding golden nonces requires an enormous amount of time and computing power.

When a block is successfully mined, the change is accepted by all of the nodes on the network and the miner is rewarded financially.

### Nodes
One of the most important concepts in blockchain technology is decentralization. No one computer or organization can own the chain. Instead, it is a distributed ledger via the nodes connected to the chain. Nodes can be any kind of electronic device that maintains copies of the blockchain and keeps the network functioning.

Every node has its own copy of the blockchain and the network must algorithmically approve any newly mined block for the chain to be updated, trusted and verified. Since blockchains are transparent, every action in the ledger can be easily checked and viewed. Each participant is given a unique alphanumeric identification number that shows their transactions.

Combining public information with a system of checks-and-balances helps the blockchain maintain integrity and creates trust among users. Essentially, blockchains can be thought of as the scalability of trust via technology.

### Public and Private Keys
How to protect blockchain transactions without requiring a third party to verify? The idea behind is PUBLIC KEY CRYPTOGRAPHY (PKC).

For a transaction on the blockchain to be complete, it needs to be signed. The steps for someone to send you a transaction are:

- A transaction is encrypted using a public key. The transaction can only be decrypted by the accompanying private key.

- Next, the transaction is signed using the private key, which proves that the transaction hasn’t been modified. The digital signature is generated through combining the private key with the data being sent in the transaction.

- Finally, the transaction can be verified as authentic using the accompanying public key.

You digitally sign a transaction to prove you’re the owner of the funds. Nodes check and authenticate transactions automatically. Any unauthenticated transactions get rejected by the network. An authentic, mined transaction on the blockchain is irreversible.

 These keys are a part of the public-key cryptography (PKC) framework. You can use these keys to send your cryptocurrency to anyone, anywhere, at any time. The public and private keys fit together as a key pair. You may share your public keys in order to receive transactions, but your private keys must be kept secret. If anyone has access to the private keys, they will also have access to any cryptocurrency associated with those keys.

**KEY TAKEAWAYS**
- The goal of public and private keys is to prove that a spent transaction was indeed signed by the owner of the funds, and was not forged.
- When you own cryptocurrencies, what you really own is a “private key.”
- Your “private key” unlocks the right for its owner to spend the associated cryptocurrencies. As it provides access to your cryptocurrencies, it should remain private.
- You can have one or multiple public keys  associated to every private key
- It’s possible to recover the public key if you own the private key. However it’s impossible to find the private key using only the public key.

### Block Rewards
As mentined above, miners join to solve the incredibly complex math problem of finding a nonce that generates an accepted hash.  Block rewards thus is the gift which is payed for the miner for being the first to solve the problem and creating a new block of verified transactions. The miners use networks of computers to do this, and every time a new block is created it is verified by all the other competing miners. Then a new math problem is introduced and the miners start over.

In bitcoin eco-system, the block reward provides an incentive for bitcoin miners to process transactions made with the cryptocurrency. Creating an immutable record of these transactions is vital for bitcoin to work as intended. The blockchain is like a decentralized bank ledger—one that can't be altered after being created. The miners are needed to verify the transactions and keep this ledger up to date. Block rewards, and to a lesser extent, transaction fees, are their payment for doing so.

Ethereum, bitcoin's main competitor as a cryptocurrency, also relies on block rewards to provide incentives to miners. With Ethereum, the reward is a digital token called "ether," which is rewarded each time a miner succeeds in providing the mathematical proof of a new block. As with bitcoin, miners are also awarded a transaction fee, known as a "gas" fee.

## Blockchain Oracles
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)
- [Decentralized Blockchain Oracles](https://blog.chain.link/what-is-the-blockchain-oracle-problem/)

Blockchain oracles are entities that connect blockchains to external systems, thereby enabling smart contracts to execute based upon inputs and outputs from the real world. For example, let’s assume Alice and Bob want to bet on the outcome of a sports match. Alice bets $20 on team A and Bob bets $20 on team B, with the $40 total held in escrow by a smart contract. When the game ends, how does the smart contract know whether to release the funds to Alice or Bob? The answer is it requires an oracle mechanism to fetch accurate match outcomes off-chain and deliver it to the blockchain in a secure and reliable manner.

The blockchain oracle problem outlines a fundamental limitation of smart contracts—they cannot inherently interact with data and systems existing outside their native blockchain environment. Resources external to the blockchain are considered “off-chain,” while data already stored on the blockchain is considered on-chain. By being purposely isolated from external systems, blockchains obtain their most valuable properties like strong consensus on the validity of user transactions, prevention of double-spending attacks, and mitigation of network downtime. Securely interoperating with off-chain systems from a blockchain requires an additional piece of infrastructure known as an “oracle” to bridge the two environments.

## Consensus
In a blockchain, to validate new entries or records to a block, a majority of the decentralized network’s computing power would need to agree to it. To prevent bad actors from validating bad transactions or double spends, blockchains are secured by a consensus mechanism such as [proof of work-PoW](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow) or [proof of stake-PoS](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/). These mechanisms allow for agreement even when no single node is in charge.

Proof-of-work is the mechanism that allows the decentralized blockchain network to come to consensus, or agree on things like account balances and the order of transactions. This prevents users from "double spending" their coins and ensures that the block chain is tremendously difficult to attack or manipulate.

Proof-of-stake is a type of consensus mechanism used by blockchain networks to achieve distributed consensus. It requires users to stake their block reward to become a validator in the network. Validators are responsible for the same thing as miners in proof-of-work: ordering transactions and creating new blocks so that all nodes can agree on the state of the network.

Proof-of-stake comes with a number of improvements to the proof-of-work system:

- better energy efficiency – you don't need to use lots of energy mining blocks
- lower barriers to entry, reduced hardware requirements – you don't need elite hardware to stand a chance of creating new blocks
stronger immunity to centralization proof-of-stake should lead to more nodes in the network
- stronger support for shard chains – a key upgrade in scaling the Ethereum network



## Miscellaneous
- [What is a blockchain](https://www.investopedia.com/terms/b/blockchain.asp)
- [Blockchain Demo](https://andersbrownworth.com/blockchain/)
- [Consensus](https://wiki.polkadot.network/docs/learn-consensus)
- [Nakamoto Consensus](https://blockonomi.com/nakamoto-consensus/)
- [Public / Private Keys](https://andersbrownworth.com/blockchain/public-private-keys/keys)
- [Layer 2 and Rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/)
- [Decentralized Blockchain Oracles](https://blog.chain.link/what-is-the-blockchain-oracle-problem/)
- [Block Rewards](https://www.investopedia.com/terms/b/block-reward.asp)
- [Run Your Own Ethereum Node](https://geth.ethereum.org/docs/getting-started)
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)
- [DAOs](https://www.investopedia.com/tech/what-dao/)