# Introduction

Documentation for [BOScoin](http://boscoin.io)'s projects, mainly Sebak, its node implementation with the [ISAAC consensus protocol](https://boscoin.io/article/introduction-of-isaac-consensus-protocol-for-bosnet/).

# ISAAC

ISAAC consensus protocol is based on FBA(Federated Byzantine Agreement) consensus protocol. The basic idea of ISAAC and FBA is so simple, nodes are connected each other in small group that can make agreement.  And entire connected groups can reach the same agreement results from small group. This small group of nodes, we call it `quorum` and entire group will be union of quorums. For more information about ISAAC and FBA, you can see [ISAAC consensus protocol for BOSNet](https://boscoin.io/article/introduction-of-isaac-consensus-protocol-for-bosnet/) and [The Stellar Consensus Protocol: A Federated Model for Internet-level Consensus](https://www.stellar.org/papers/stellar-consensus-protocol.pdf).

For Korean developers, we [translated the SCP paper to Korean](https://github.com/bosnet/papers/blob/master/The-Stellar-Consensus-Protocol/The-Stellar-Consensus-Protocol.md).

This documentation is also [available online](https://bosnet.github.io/sebak/api/).
