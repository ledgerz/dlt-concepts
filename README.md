# DLT Concepts

This README introduces the main technical concepts to understand Distributed Ledger Technologies, the umbrella term for emerging Blockchain and Direct Acyclic Graph (DAG) technologies.

# Core "unique" concepts

## Proof of Work

**Why:** For security and enabling "correct" consensus<br>
**What:** The resulting hash that "proofs" that a certain amount of computational power has been invested<br>

[![pow](https://user-images.githubusercontent.com/10008938/38468286-edf66fac-3b43-11e8-9285-0a6e151c57c2.png)](https://user-images.githubusercontent.com/10008938/38468110-d82e2b76-3b41-11e8-9771-2225bab6b3f5.png)


More detailed explanations: [Wikipedia](https://en.wikipedia.org/wiki/Proof-of-work_system) [bitcoin-wiki](https://en.bitcoin.it/wiki/Proof_of_work)

One of the best ways to really understand it - implement one yourself:
- [JavaScript Example](https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.js)
- [Python Example](https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.py)
- [Swift Example](https://github.com/ledgerz/swift-blockchain)
- [Ruby Example](https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.rb)
- [Go Example](https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.go)

**Recommendation:** First try to implement it from scratch, then look at an example in a different language from your implementation and redo it.

## Consensus

**Why:** Required for decentralization<br>
**What:** A dynamic way of reaching agreement in a group<br>

*Why is achieving consensus so difficult?*<br>
-> Starting point: [Two generals problem](https://en.wikipedia.org/wiki/Two_Generals%27_Problem)

*Amazing E-Mail from Satoshi in 2008 explaining how consensus & proof of work play together:*<br>
[Email: Proof of Work to solve consensus in the Byzantine Generals Problem](https://www.mail-archive.com/cryptography@metzdowd.com/msg09997.html)

[Short explanation with visuals](https://mastanbtc.github.io/blockchainnotes/consensustypes/)

[Consensus in Blockchain Systems in short (Medium Article)](https://medium.com/@chrshmmmr/consensus-in-blockchain-systems-in-short-691fc7d1fefe)

#### Great links to deepen the understanding of Consensus Systems:

[Consensus in Blockchain Systems (David Terry, Video)](https://www.youtube.com/watch?v=6P8OWKRaz2k&index=6&t=8s&list=PLJ126e0nszLcdzW8lzA4hjYLZh5YvSaTu)

[Consensus Systems with Ethan Buchman (Podcast)](https://softwareengineeringdaily.com/2018/03/26/consensus-systems-with-ethan-buchman/)


# Basic underlying concepts

### Public-key / private-key (asymmetric cryptography)

### Hashing function

### Merkle Tree




