# bitcoin terms

## Block
* Blocks are found in the Bitcoin block chain. Blocks connect all transactions together. 
* Transactions are combined into single blocks and are verified every ten minutes through mining. 
* Each subsequent block strengthens the verification of the previous blocks, making it impossible to double spend bitcoin transactions.

## Block Chain
* Bitcoin block chain is a public record of all Bitcoin transactions. 
* “public ledger.” The block chain shows every single record of bitcoin transactions in order, dating back to the very first one.
* The entire block chain can be downloaded and openly reviewed by anyone, or you can use a block explorer to review the block chain online.

## Block Height
* The block height is just the number of blocks connected together in the block chain. 
* Height 0 for example refers to the very first block, called the “genesis block.”

## Change
* Let’s say you are spending $1.90 in your local super market, and you give the cashier $2.00. 
* You will get back .10 cents in change. The same logic applies to bitcoin transactions. 
* Bitcoin transactions are made up of inputs and outputs. 
* When you send bitcoins, you can only send them in a whole “output.” The change is then sent back to the sender.

## Confirmation
* A confirmation means that the bitcoin transaction has been verified by the network, through the process known as mining. 
* Once a transaction is confirmed, it cannot be reversed or double spent. Transactions are included in blocks.

## Difficulty
* Difficulty is directly related to Bitcoin mining, and how hard it is to verify blocks in the Bitcoin network. 
* Bitcoin adjusts the mining difficulty of verifying blocks every 2016 blocks. 
* Difficulty is automatically adjusted to keep block verification times at ten minutes.

## Double Spend
* If someone tries to send a bitcoin transaction to two different recipients at the same time, this is double spending. 
* Once a bitcoin transaction is confirmed, it makes it nearly impossible to double spend it. 
* The more confirmations that a transaction has, the harder it is to double spend the bitcoins.

## Halving
* Bitcoins have a finite supply, which makes them scarce. The total amount that will ever be issued is 21 million. 
* The number of bitcoins generated per block is decreased 50% every four years. 
* This is called “halving.” The final halving will take place in the year 2140.

## Mining
* Bitcoin mining is the process of using computer hardware to do mathematical calculations for the Bitcoin network in order to confirm transactions. 
* Miners collect transaction fees for the transactions they confirm and are awarded bitcoins for each block they verify.

## Private Key
* A private key is a string of data that shows you have access to bitcoins in a specific wallet. 
* Think of a private key like a password; private keys must never be revealed to anyone but you, as they allow you to spend the bitcoins from your bitcoin wallet through a cryptographic signature.





51% Attack & Eclipse Attack
Bitcoin
Blockchain
Blockchain Attacks
Blockchain Explorer
Blocknet
Centralized storage
Centralized/Decentralized
Consensus Algorithm
Cryptocurrency
Cryptography
Decentralized Ledger
Difficulty
Ether
Ethereum
Gas
Genesis Block
Hard Fork
Hash rate
Hashes
Hashpower
Ledger
Merkel Tree & Root
Miner
Mining
Multichain
Peer-to-peer network
Private Ledger
Public & Private Key (PKI Infrastructure)
Public Ledger
Rewards
Signing a Transaction
Smart Contract
Solidity (Language for writing Smart Contracts)
Symmetric Key
Transaction
Transaction Confirmation
Use cases of Blockchain
ZCash



* **Public Key Cryptography**. Alice has a public key and private key. She can use her private key to create a digital signature, and Bob can use Alice’s public key to verify that a signature is really from Alice’s private key, i.e., really from Alice. When you create an Ethereum or Bitcoin wallet the long ‘0xdf…5f’ address is a public key and the private key is stored somewhere. A Bitcoin wallet service like Coinbase stores your wallet’s complementary private key for you, or you can store it yourself. If you lose your private key for a wallet with real funds you’ll lose all your funds forever, so it’s good to back up your keys. It hurts to learn this the hard way! I’ve done it.

* **Peer-to-Peer Networking**. Like BitTorrent, all Ethereum nodes are peers in a distributed network, there’s no centralized server. [In the future, there’ll be hybrid semi-centralized services for Ethereum as a convenience to users and developers, more on that later.]

* **Blockchain**. Like a global ledger or simple database of all transactions, the entire history of all transactions on the network.

* **Ethereum Virtual Machine**. So you can write more powerful programs than on top of Bitcoin. It refers to the blockchain, what executes smart contracts, everything.

* **Node**. Using this to mean you can run a node and through it read and write to the Ethereum blockchain, i.e., use the Ethereum Virtual Machine. A full node has to download the entire blockchain. Light nodes are possible but in the works.

* **Miner**. A node on the network that mines, i.e., works to process blocks on the blockchain. You can see a partial list of live Ethereum miners here: stats.ethdev.com.

* **Proof of Work**. Miners compete to do some math problem. The first one to solve the problem (the next block on the Blockchain) wins a reward: some ether. Every node then updates to that new block. Every miner wants to win the next new block so are incentivized to keep up to date and have the one true blockchain everybody else has, so the network always achieves consensus. [Note: Ethereum is planning to move to a Proof of Stake system without miners eventually, but that’s beyond noob scope.]

* **Ether. Or ETH for short**. It’s a real digital currency you can buy and use! Here’s a chart from one of several exchanges for it. At the time of writing, 1 ETH is worth about 65 cents in USD.

* **Gas**. Running and storing things on Ethereum costs small amounts of ether. Keeps things efficient.

* **DApp**. Decentralized App, what applications using smart contracts are called in the Ethereum community. The goal of a DApp is (well, should be) to have a nice UI to your smart contracts plus any extra niceties like IPFS (a neat way to store and serve stuff in a decentralized network, not made by Ethereum but a kindred spirit). While DApps can be run from a central server if that server can talk to an Ethereum node, they can also be run locally on top of any Ethereum node peer. [Take a minute: unlike normal webapps, DApps may not be served from a server. They may use the blockchain to submit transactions and retrieve data (important data!) rather than a central database. Instead of a typical user login system, users may be represented by a wallet addresses and keep any user data local. Many things can be architected differently from the current web.]


