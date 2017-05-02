Welcome to Fabric
https://hyperledger-fabric.readthedocs.io/en/latest/


https://blockchain-finance.com/wp-content/uploads/2016/03/Hyperledger-architecture.png


https://www.altoros.com/blog/tag/hyperledger/

Introduction to Blockchain and the Hyperledger Project
https://www.slideshare.net/ManuelGarcia122/introduction-to-blockchain-and-the-hyperledger-project


https://www.ibm.com/blockchain/hyperledger.html

https://www.hyperledger.org/

https://blog.craftworkz.co/run-hyperledger-locally-with-docker-4f3bcb815c03

https://www.altoros.com/blog/hyperledger-ethereum-discussion-makes-p2p-b2b-distinction/

https://www.altoros.com/blog/how-hyperledger-fabric-delivers-security-to-enterprise-blockchain/


Blockchain technology for business

https://medium.com/tag/hyperledger
As one of the folks who answered in that thread (and has experience with Hyperledger) I am happy to answer any questions. In brief:
– The Hyperledger Project is underneath the Linux Foundation (not IBM), and is an incubator for multiple project submissions, including: Fabric (permissioned blockchain), Sawtooth Lake (also permissioned but adds Proof of Elapsed Time as the consensus model), Iroha (a lightweight C++ blockchain), Cello (a rapid deployment scheme for blockchains), Dashboard (what it says), and soon Corda (R3’s distributed ledger for banking).
– Because it is run under the Linux Foundation it is true open source, and think of Hyperledger as being similar to Apache in that it curates multiple projects.
– The main project most people associate with Hyperledger is Fabric. IBM is the primary (but not the sole) source of code for this project, and again it is a permissioned (vs. permissionless) ledger in that all of the participants are identified and authenticated, i.e. it is not anonymous. It utilizes smart contracts similarly to Ethereum but does not use the Solidity language; it also does not use Proof-of-Work (or Proof-of-Stake) algorithms for consensus, instead using Practical Byzantine Fault Tolerance. But both the consensus framework and the security framework are *pluggable*, so that in theory you can swap in other consensus and security mechanisms. There are a number of other differences, but fundamentally Fabric is designed from the outset to be a blockchain for enterprise and private networks where identity must be known or at least tracked (which is most industries to some extent). Ethereum differs in its open source model and is a cryptocurrency-based anonymous and public blockchain platform; typically anyone can join an Ethereum network, whereas to join a Fabric network one must be added by a security authority.


Lot of docs
https://github.com/TarantulaTechnology/Documents-Blockchain

# Demo code
https://github.com/Manish-Men/Hyperledger - Hello World
https://github.com/gazbert/hyperledger-mortgage-demo
https://github.com/hyperledger/iroha
https://github.com/timblankers/hyperledger-hackathon
s

# DOcker
https://github.com/yeasy/docker-hyperledger


https://github.com/hyperledger/composer-sample-networks

https://github.com/hyperledger/composer-sample-applications

https://github.com/keoja/hyperledger-ansible

https://github.com/Junboh/hyperledger
https://github.com/springblock/Hyperledger
https://github.com/hyperledger/composer

https://github.com/Junboh/hyperledger
https://github.com/Bartman250/hyperledgergetgoing
https://github.com/IBM-Blockchain/fabric-images
https://github.com/harrijk/fabric-tools
https://github.com/yeasy/blockchain_guide/tree/master/ethereum
https://github.com/piitaya/hyperledger-starter-app
https://github.com/erm2wi/hyperledgerlearning
https://github.com/GruberQZ/energy-trading-marketplace
https://github.com/jumpjumpbean/HyperledgerHackathon


https://github.com/satoshikumano/Hyperledger-Example
https://github.com/pong-pantola/hyperledger-basics
https://github.com/soramitsu/iroha-demo-javascript
https://github.com/rameshthoomu/hyperledger.github.io
https://github.com/vishwass/Hyperledger-Setup-tutorials
https://github.com/Srinivasan1983/Hyperledger-Simple-CRUD-Operation
https://github.com/BlueHC/hyperledger-learn-chaincode
https://github.com/BlueHC/hyperledger-dev-setup
https://github.com/clkwong/testing
https://github.com/rtang03/fabric-cookbook
https://github.com/predix/fabric-acceptance-tests
https://github.com/DecodedCo/blockchain-vote
https://github.com/sujayv/basic-blockchain-app
https://github.com/xspeedcruiser/fabric-exercise
https://github.com/jellevdp/advertisement-demo
https://github.com/tiero/bpay-mobile-app

