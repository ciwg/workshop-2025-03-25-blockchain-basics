class: center, middle

# Blockchain Workshop

---

## Introduction to Blockchain
- What is blockchain?
  - Blockchain is a decentralized *ledger* technology that records transactions across a network of computers. The data is stored in blocks that are linked together in a chain, where each block contains a cryptographic hash of the previous block, a timestamp, and transaction data.
- Key properties of blockchain:
    - **Immutability** - Once a block is added to the blockchain, it cannot be altered or deleted.
    - **Security** - Transactions are *cryptographically* secured and verified by the network.
    - **Consensus** - The network agrees on the validity of transactions through consensus mechanisms like *Proof of Work* or *Proof of Stake*.

---

## Cryptographic Hash Functions
- Example: SHA-256
- Variable input size, fixed output size (64 characters)
- One-way function - infeasible to reverse
- Information is compressed into a fixed-size hash, e.g., 256 bits. This inherently makes it impossible to reverse the hash to obtain the original data.
- Deterministic and collision-resistant (theroretically impossible to find two different inputs that produce the same hash)

---

## Hash Chaining & Block Structure
- Blocks contain:
  - Previous block hash
  - Timestamp
  - Transactions in the block
  - Nonce (for PoW) - a nonce is a random number that is used to vary the output of a cryptographic hash function
- Adding a random nonce and hashing
- Leads into **Proof of Work**

---

## Proof of Work (PoW)
- Miners compete to solve a cryptographic puzzle
- Target difficulty dynamically adjusted so that transactions rate is predictable
- ie. Bitcoin 1 block per 10 minutes on average
- Each block added to the Bitcoin blockchain is ~1MB. 
- Approximately 4,000 Bitcoin transactions can fit into this 1MB block. Since there is one new Bitcoin block added every 10 minutes on average, this suggests that Bitcoin can manage only ~7 transactions / second.

---

## Proof of Stake (PoS)
- Ethereum switched to PoS
- Validators "stake" cryptocurrency
- Voting-based consensus

---

## Mining & Block Rewards
- Incentives: block reward + transaction fees
- Bitcoin halving events reduce rewards
- Mining pools vs. solo mining
- Security: 51% attack risk

---

## Transactions & Mempool
- Transactions enter the **mempool**
- Miners prioritize high-fee transactions
- Structure: inputs & outputs model
- Fees incentivize miners

---

## Merkle Trees & Data Structure
- Bitcoin transactions stored in a **Merkle Tree**
- Efficient verification of transactions

---

## Public & Private Keys
- Accounts are pseudonymous
- Public keys are derived from private keys
- Public keys are used to receive assets
- Private keys are used to sign transactions
- Losing private key = losing assets

---

## Wallets & Security
- A wallet stores **private keys**
- Self-custody vs. exchange wallets
- Risks: **FTX collapse**, hacking
- Best practices: hardware wallets, paper backups

---

## Blockchain Types & Governance
- **Permissionless**: Bitcoin, Ethereum
- **Permissioned**: Banks, private ledgers (Quorum)
- Governance models: BIP, EIP, DAOs

---

## Smart Contracts
- **Bitcoin Script**: Non-Turing complete
- **Ethereum Solidity**: Turing-complete smart contracts
- **Gas fees** prevent infinite execution

---

## Tokenization
- **Native tokens**: Bitcoin, Ethereum, Cardano
- **Non-Native tokens**: ERC-20 (fungible), ERC-721 (NFTs)
- Risks: **Solidity bugs, DAO hack**

---

## Blockchain Challenges
- **Scalability**: Bitcoin (~7 TPS), Ethereum (~30 TPS)
- **Security**: 51% attacks, exploits, hacking
- **Legal Risks**: AML, regulations

---

## Future of Blockchain
- Web3 applications
- Decentralized identity & governance
- AI & blockchain integration

