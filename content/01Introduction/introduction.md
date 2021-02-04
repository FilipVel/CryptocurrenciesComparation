## Blockchain definition
***

Emerged from the need of an electronic payment system that will not rely on a trusted third party as a central authority e.g. banks and governments, the blockchain technology is a common discussion topic among tech enthusiasts. First introduced back in 2008 by Satoshi Nakamoto, blockchain seems to address this challenge by proposing a purely peer-to-peer distributed timestamp server solution that generates computational proof of the chronological order of transactions. [[*1, The white paper*]](https://bitcoin.org/bitcoin.pdf) 
What we today know as a blockchain is a growing sequence of records called blocks, designed to be resistant to modification of its data by implementing a cryptographic hashing algorithm. It is an open-source, distributed ledger that allows recording transactions between two parties efficiently and in a verifiable and permanent way. [[*2, The Truth about Blockchain*]](https://hbr.org/2017/01/the-truth-about-blockchain) Each of the blocks contains hashed transactions of the previous block in the blockchain, meaning that it prevents data inconsistency as any change is immediately noticed. [[*3, Wikipedia*]](https://en.wikipedia.org/wiki/Blockchain) This is an essential concept that makes blockchain a revolutionary discovery in a world dependent on traditional fiat systems.

## Blockchain Types
***
Up until now there are at least four types of blockchain networks [[4]](https://101blockchains.com/types-of-blockchain/), 
[[5]](https://data-flair.training/blogs/types-of-blockchain/),
[[6]](https://dragonchain.com/blog/differences-between-public-private-blockchains),
[[7]](https://blockstream.com/sidechains.pdf),
[[8]](https://hackernoon.com/13-sidechain-projects-every-blockchain-developer-should-know-about-804b65364107):
- **Public blockchains** - non-restrictive, permission-less distributed ledger system e.g. Bitcoin, Litecoin, Etherium
- **Private blockchains (Distributed Ledger, DLT)** - a restrictive or permission blockchain operative only in a closed network e.g. Multichain, Corda
- **Hybrid blockchains** - a flexible blockchain that implements a combination of centralised and decentralised features e.g. Dragonchain, XinFin.
- **Sidechains** - a blockchain that validates data from other blockchains; runs in parallel with a primary blockchain, but independently of it e.g. Plasma, Liquid.


### How it works

Rather than a completely new technological discovery, Blockchain is considered as a revolutionary innovation thanks to the combination of several existing technologies. According to CoinDesk [[9]](https://www.coindesk.com/learn/blockchain-101/how-does-blockchain-technology-work), the three component technology that make Blockchain when applied jointly are:
1. Private key cryptography
2. A distributed network with a shared ledger
3. The blockchain protocol governing incentivisation

## Concepts/Terms/Definitions
***

### Private key cryptography
This type of cryptography uses a pair of a public key and a private key to create a digital identity reference which provides strong control of ownership. Public keys are widely distributed, on the other hand, private keys are kept secret. [[10]](https://medium.com/coinmonks/blockchain-public-private-key-cryptography-in-a-nutshell-b7776e475e7c#:~:text=Blockchain%20makes%20use%20of%20several%20different%20types%20of%20cryptography.&text=Public%20key%20cryptography%20uses%20a,key%20to%20perform%20different%20tasks.&text=Using%20a%20person's%20public%20key,can%20decrypt%20and%20read%20it). For an example, you could think of the public key as your bank account number and the private key as your password which you use to log into your bank account.

This concept achieves the goal to prove that a spent transaction was indeed signed by the owner of the funds, and was not forged, all occurring over a public blockchain network between peers. [[11]](https://www.ledger.com/academy/blockchain/what-are-public-keys-and-private-keys)

### A distributed network with a shared ledger

While the private key cryptography solves the authentication, authorisation still remains a challenge to be tackled. This is where a distributed network comes in, which enables approval of transactions and permissions. DLT allows data to be stored globally on thousands of servers and lets anyone on the network see all entries in almost near real-time. Therefore, the need of a central authority or intermediary to process and validate transactions i.e. a bank, is eliminated.[[12]](https://www.computerworld.com/article/3191077/what-is-blockchain-the-complete-guide.html)


### The Blockchain Protocol

Blockchain uses a technique to create and verify a continuously growing, append-only data structure which serves the function of a ledger. New transactions which include encrypted data are collectively determined as valid and added to the block only by a previous confirmation of the block’s validity by all network participants according to a predefined validation algorithm. 
[[13]](https://olc.worldbank.org/system/files/122140-WP-PUBLIC-Distributed-Ledger-Technology-and-Blockchain-Fintech-Notes.pdf)

To simplify the concept and understand it better, we will define the following terms: 
- A **block** is a container data structure that aggregates transactions for inclusion in the public ledger (the blockchain). It contains a digital signature, a timestamp and other relevant information. 
- **Mining** is a process of creating new bitcoin by solving complex mathematical calculation for the network to confirm transactions by high-powered computers. 

The protocol can be elaborated in the following steps: [[14]](https://www.investopedia.com/terms/b/blockchain.asp)
- A new transaction is entered.
- The transaction is transmitted through the network of P2P computers across the world.
- The network participants perform mining calculations to confirm the validity of the transaction.
- Once confirmed, the transaction is complete.
- The blocks are chained together, creating a long history of permanent transactions.
- Once confirmed to be legitimate transactions by consensus, they are clustered into blocks.

Since the blockchain that took the most computing work to generate (the longest version) is considered to be ‘the correct one’, this approach makes it very difficult to control and/or alter the transactions in the network, although not impossible. However, it would take a massive CPU power to hack it - an entity needs to control more than 51% of the total network’s computing (hashing) power. [[15]](https://www.lexology.com/library/detail.aspx?g=bf19a436-52a9-47ea-b2c4-bd9afe4065d6)

Hash rate is a measuring unit of the processing power of the network, i.e. when the network reached a hash rate of 10 Th/s, it meant it could make 10 trillion calculations per second. 
[[16]](https://bitcoin.org/en/vocabulary#cryptography)

The current hash rates for the cryptocurrencies we are comparing at the time of writing are:
- Bitcoin - 142.66M TH/s
- Litecoin - 253.58 TH/s
- Bitcoin cash - 1.28 EH/s