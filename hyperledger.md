https://www.ibm.com/blockchain/hyperledger.html

https://www.hyperledger.org/

https://blog.craftworkz.co/run-hyperledger-locally-with-docker-4f3bcb815c03

Blockchain technology for business

https://medium.com/tag/hyperledger
As one of the folks who answered in that thread (and has experience with Hyperledger) I am happy to answer any questions. In brief:
– The Hyperledger Project is underneath the Linux Foundation (not IBM), and is an incubator for multiple project submissions, including: Fabric (permissioned blockchain), Sawtooth Lake (also permissioned but adds Proof of Elapsed Time as the consensus model), Iroha (a lightweight C++ blockchain), Cello (a rapid deployment scheme for blockchains), Dashboard (what it says), and soon Corda (R3’s distributed ledger for banking).
– Because it is run under the Linux Foundation it is true open source, and think of Hyperledger as being similar to Apache in that it curates multiple projects.
– The main project most people associate with Hyperledger is Fabric. IBM is the primary (but not the sole) source of code for this project, and again it is a permissioned (vs. permissionless) ledger in that all of the participants are identified and authenticated, i.e. it is not anonymous. It utilizes smart contracts similarly to Ethereum but does not use the Solidity language; it also does not use Proof-of-Work (or Proof-of-Stake) algorithms for consensus, instead using Practical Byzantine Fault Tolerance. But both the consensus framework and the security framework are *pluggable*, so that in theory you can swap in other consensus and security mechanisms. There are a number of other differences, but fundamentally Fabric is designed from the outset to be a blockchain for enterprise and private networks where identity must be known or at least tracked (which is most industries to some extent). Ethereum differs in its open source model and is a cryptocurrency-based anonymous and public blockchain platform; typically anyone can join an Ethereum network, whereas to join a Fabric network one must be added by a security authority.
