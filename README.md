# custom-java-blockchain

A personal implementation of a custom blockchain in Java. This is an exercise to understand the architecture 
and technical details of a Blockchain.

Implements: 
- Blockchain structure
- Proof-of-work.
- Allows users to create wallets with ‘new Wallet();’
- Provides wallets with public and private keys using Elliptic-Curve cryptography.
- Secures the transfer of funds, by using a digital signature algorithm to prove ownership.
- Allow users to make transactions on the blockchain with ‘Block.addTransaction(walletA.sendFunds( walletB.publicKey, 20));’

Starts genesis block with a total ammount of 100 coins.

Requires Java 1.8.
