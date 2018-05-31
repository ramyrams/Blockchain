
# Blockchain
* Web3
* Blockchain Intro
Which Blockchain?
* Tokens & Cryptoeconomics
* Smart Contracts
* dApps
* DAOs
* ICOs

![InfoGraphic](https://coinhooked.com/introduction-e-gov-blockchain/)

https://blockchainhub.net/blockchain-intro/



Free Course  ALready registered
https://academy.b9lab.com/courses/B9lab/X16-0/2016/courseware/350259f977104a77a5708ac18c38824a/

# Blockchain

Good introduction
https://blog.craftworkz.co/dip-your-toe-into-smart-contracts-with-ethereum-cf8aa476d0d7


website vs Dapp

Front End → API → Database

A Dapp is very similar to a traditional web application. The front end uses the exact same technology to render the page. The one critical difference is that instead of an API connecting to a Database, you have a Smart Contract connecting to a blockchain.

You can think of a Dapp like this:

Front End → Smart Contract → Blockchain

A Dapp is a ‘blockchain enabled’ website, where the Smart Contract is what allows it to connect to the blockchain.

Smart contract is like a character. Dapp is like a word. The difference is not in the length but in the depth of meaning. The later has a complete one (makes sense as is). The former doesn’t (it is supposed to be an actor in the system but at the different hierarchy level).

Dapps is decentralized applications built on top of blockchain technology. Some dapps are built on it’s own blockchain while most are based on popular blockchain networks like Bitcoin & Ethereum. Use the tools in the sidebar to find dapps with specific features built on top of certain blockchains.

https://medium.com/@micheledaliessi/how-does-the-blockchain-work-98c8cd01d2ae
# DApp Ecosystem
Decentralized Data
Decentralized Wealth
Decentralized Identity
Decentralized Computing
Decentralized Bandwidth
Decentralized Markets for Decentralized Assets
Practical Decentralization

Dapp Economics


An Introduction to Ethereum and Smart Contracts: a Programmable Blockchain
https://auth0.com/blog/an-introduction-to-ethereum-and-smart-contracts-part-2/

An Introduction to Ethereum and Smart Contracts: Bitcoin & The Blockchain
https://auth0.com/blog/an-introduction-to-ethereum-and-smart-contracts/


# Ethereum
	https://medium.com/@ConsenSys/very-deep-dive-on-ethereum-reading-list-f5b1122e5990
	https://ethereum.github.io/go-ethereum/
	https://ethereum.org/greeter
	https://ethereum.org/token
	https://ethereum.org/crowdsale
	https://ethereum.org/dao
	
	pyethereum - https://github.com/ethereum/pyethereum



https://medium.com/wearetheledger/live-from-eventhorizon-blockchain-energy-644149f8331b

# Semantic Ethereum
	https://media.consensys.net/ethon-introducing-semantic-ethereum-15f1f0696986
# Smart Contracts 
# DApp Frameworks and Tools
	https://dappsforbeginners.wordpress.com/
# Solidity
# Ethereum Clients
	* Ethereum has several different client implementations (meaning ways to run a node to interact with the Ethereum network) including C++, Go, Python, Java, Haskell, etc.
	* a gui-based client in development, AlethZero.
	* the Go language one (go-ethereum) http://ethereum.github.io/go-ethereum/
	* on other days a tool called testrpc that uses the Python client, pyethereum. https://github.com/ethereum/pyethereum
	* Interactive Console. https://github.com/ethereum/go-ethereum/wiki/JavaScript-Console
	* JSON RPC  https://github.com/ethereum/wiki/wiki/JSON-RPC
	* Running a node on a test network. If you install a client like geth and run it on the live network, it will take a while to download the entire blockchain and sync with the network. 
	* testrpc. You can run a test network using geth, or another fast way of getting a testnet running is using testrpc. 
	
# Smart Contract Languages
	* To write smart contracts there are a few different languages: 
	* ** Solidity** , which is like JavaScript and has .sol as a file extension, Serpent, Python-like with extension .se
	* ** solc**  Compiler. After writing a contract in Solidity, use solc to compile it. It’s from the C++ libraries (different implementations complementing each other again) which can be installed here.
	* ** web3.js API** 
	
	https://github.com/ConsenSys/smart-contract-best-practices
	
# DApp-building Frameworks
	* **Trufle and Embark**. The one that got me started is Truffle. (Before Truffle I watched a group of smart student interns last summer code stuff for a sleepless hackathon (albeit with terrific results) and shrank back in fear. Then Truffle came along and did a lot of the nitty gritty stuff for you, so you can start writing-compiling-deploying-testing-building DApps right away.) Another very similar framework for building and testing DApps is Embark. Between those two, I’ve only used Truffle, but there are very successful DApp devs in both camps.
	* **Meteor**. Another stack a lot of DApp devs use include web3.js + Meteor which is a general webapp framework (The ethereum-meteor-wallet repo has a good starter example, and SilentCiero is building a lot of Meteor integrations with web3.js and DApp boilerplates).
	* **APIs**. BlockApps.net is creating a RESTful API for DApps based on a Haskell node they run as a centralized service to save you the trouble of running a local Ethereum node. This departs from the completely decentralized model of DApps but is useful when running an Ethereum node locally isn’t realistic. For example if you want to serve your DApp to users who won’t be running local nodes either and reach a wider audience with just a web browser or mobile device. BlockApps has a command line tool called bloc in the works that can be used after creating a developer account with them.
	
# Smart Contract IDE

* **IDEs**.There’s a Mix IDE for writing contracts put out by Ethereum. Haven’t tried it but will soon.

* **Browser-based IDEs**. The Solidity real-time compiler and Cosmo are both a fast way to get started compiling your smart contracts right away in a browser. You can even point your local node at these hosted instances by opening up a port (you should trust the site and not have your life savings in ether on your local node for that! See the Cosmo UI for instructions on how to do this with geth). But once your contract is working ok it’s nice to use a framework for adding a UI and packaging it all up as a DApp, which is what Truffle does and will be explained in the programming part later.

* Another powerful enterprise-y browser IDE is in the works by Ether.Camp. Their IDE comes with a sandbox test network with an auto-generated GUI for testing (instead of writing tests manually as shown in the tutorial later) as well as a sandbox transaction explorer at test.ether.camp. When you’re ready to deploy your contract for semi-real, using their testnet can a good way to confirm your smart contract’s working as expected on a closer-to-real testbed. The same explorer for the live Ethereum network is at frontier.ether.camp and it shows details about every transaction ever. Ether.Camp’s IDE is invite-only for eager guinea pigs at time of writing but will be launched soon.

# Workflow for Deploying Smart Contracts
The workflow is:

1. **Start** an Ethereum node (e.g. geth or testrpc)
2. **Compile** your Solidity smart contract using solc => get back the binary
3. **Deploy** your compiled contract to the network. (This step costs ether and signs the contract using your node’s default wallet address, or you can specify another address.) => get back the contract’s blockchain address and ABI (a JSON-ified representation of your compiled contract’s variables, events and methods that you can call)
4. **Call** stuff in the contract using web3.js’s JavaScript API to interact with it (This step may cost ether depending on the type of invocation.)

![1](https://consensys.github.io/developers/images/front-end.png)





# Truffle
For many types of Dapps (Distributed Apps), Truffle does everything you could want: It compiles your blockchain contracts, injects them into your web app, and can even run a test suite against them!

http://truffle.readthedocs.io/en/latest/

https://metamask.io/

# Metamask
With Metamask, all your users need to do is install the Chrome plugin, and they will have their own secure blockchain accounts right there in the convenience of their browsers.

https://medium.com/metamask/developing-ethereum-dapps-with-truffle-and-metamask-aa8ad7e363ba


Truffle Tricks for Ethereum Development: Dispelling 8 Myths & First Impressions
https://media.consensys.net/truffle-tricks-for-ethereum-development-dispelling-8-myths-first-impressions-ecb3edf88207

# Sample App
Ethereum Wallet Ðapp https://github.com/ethereum/meteor-dapp-wallet

# For .NET Development
# nethereum
http://www.nethereum.com/ - Bringing the love of Ethereum to .Net

Solidity Integration with Visual Studio
https://media.consensys.net/solidity-integration-with-visual-studio-7f25ea1bde71

# OpenBazaar
	https://openbazaar.org/
	
	Why Make OpenBazaar?
What Is OpenBazaar?
How Does OpenBazaar Work?
How to Install OpenBazaar
What Could OpenBazaar Have Done Better?

# La’Zooz
	http://lazooz.org/
	


What Is La’Zooz?
UX





Hyperledger Fabric vs Ethereum vs Ripple vs Bitcoin
https://goupadhyblog.wordpress.com/2017/01/16/hyperledger-vs-ehtereum-vs-ripple-vs-bitcoin/


https://goupadhyblog.wordpress.com/2017/02/10/consensus-in-hyperledger-based-bluemix-blockchain-apps/

https://goupadhyblog.wordpress.com/2017/02/08/setup-blockchain-network-in-minutes-using-ibm-bluemix/

https://goupadhyblog.wordpress.com/2017/02/07/how-to-write-smart-contract-chaincode-in-hyperledger-based-blockchain-applications/

https://goupadhyblog.wordpress.com/2017/02/02/hyperledger-based-bluemix-blockchain-application-architecture-and-components/


https://goupadhyblog.wordpress.com/2017/01/31/what-blockchain-is-not/

https://goupadhyblog.wordpress.com/2017/01/16/hyperledger-vs-ehtereum-vs-ripple-vs-bitcoin/


https://goupadhyblog.wordpress.com/2017/01/15/potential-blockchain-use-cases/

# Video
* [Bitcoin and Cryptocurrency Technologies](https://www.coursera.org/learn/cryptocurrency/home/welcome)
* [IBM Blockchain for developers](https://developer.ibm.com/courses/all-courses/blockchain-for-developers/)
* [3 Free Courses](http://courses.blockgeeks.com/collections)
* [Bitcoin & the Blockchain](https://onemonth.com/courses/blockchain)
* [Video lectures and courses](https://github.com/digital-dreamer/blockchain-programming/wiki/Video-lectures-and-courses)
* [Welcome to Ethereum 101!](https://academy.b9lab.com/courses/B9lab/X16-0/2016/info)
* [Blockchain University Courses](http://blockchainu.co/upcoming/)
* [INVESTIGATING THE POTENTIAL OF BLOCKCHAINS](http://blockchain.open.ac.uk/)
* [Blockchain Academy](http://www.blockchain.org.in/)
* [Microsoft Blockchain as a Service](https://mva.microsoft.com/en-us/training-courses/microsoft-blockchain-as-a-service-17104?l=aZrQbG3SD_3206218965)
* [Free Videos](http://www.blockchainworkspace.com/training/free/)
* [Blockchain University](https://www.youtube.com/channel/UCJ5uHx90mZGlK0lC-GSmtzw)
* [Ethereum](https://www.youtube.com/user/ethereumproject)


	
# Lighthouse

	https://bravenewcoin.com/news/lighthouse-tackles-decentralized-crowdfunding/
	http://bitcoinist.com/decentralized-crowdfunding-app-lighthouse-getting-traction/
	https://techcrunch.com/2014/05/23/lighthouse-is-a-crowdfunding-platform-built-on-top-of-bitcoin/
	
	Functionality
SPV Wallets
Identity

# URL
* [A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://consensys.github.io/developers/articles/101-noob-intro/)

# Free Course
http://courses.blockgeeks.com/courses/blockchain-faqs-answered-in-1-hour

http://courses.blockgeeks.com/courses/blockchain-glossary-learn-blockchain-frequently-used-terms


https://github.com/oreillymedia/decentralized_applications

The Supply Circle: How Blockchain Technology Disintermediates the Supply Chain
https://media.consensys.net/the-supply-circle-how-blockchain-technology-disintermediates-the-supply-chain-6a19f61f8f35

What Is Ethereum? And How Does It Work?
https://dinardirham.com/blog/what-is-ethereum-and-how-does-it-work/




Dapps (Decentralized Apps)
https://cryptojunction.com/dapps/


# Course
https://academy.b9lab.com/courses/course-v1:B9lab+ETH-11+2017-04/about
https://academy.b9lab.com/courses/B9lab/X16-0/2016/about
https://academy.b9lab.com/courses/B9lab/CTO1/2017-03/about
https://academy.b9lab.com/courses/course-v1:B9lab+ETH-12+2017-05/about
https://academy.b9lab.com/courses/course-v1:B9lab+ETH-13+2017-06/about
https://academy.b9lab.com/courses/course-v1:B9lab+CTO3+2017-05/about
https://academy.b9lab.com/courses/course-v1:B9lab+ETH-14+2017-07/about

http://courses.blockgeeks.com/
http://courses.blockgeeks.com/courses/ultimate-blockchain-course-building-blockchain-application-aws
http://courses.blockgeeks.com/courses/best-solidity-tutorial-for-ethereum-smart-contracts-on-internet
http://courses.blockgeeks.com/courses/ethereum-developer

https://www.udemy.com/ethereum-developer/
https://www.udemy.com/the-basics-of-blockchain/
https://www.udemy.com/blockchain101/
https://www.udemy.com/ethereum/
https://www.udemy.com/blockchain-developer/
https://www.udemy.com/best-solidity-tutorial-course-ethereum-blockchain-development/


# Free Course
http://courses.blockgeeks.com/courses/take/blockchain-faqs-answered-in-1-hour/lessons/990989-1-introduction-overview
http://courses.blockgeeks.com/courses/take/blockchain-glossary-learn-blockchain-frequently-used-terms/lessons/991023-1-introduction-overview
http://courses.blockgeeks.com/courses/take/bitcoin-and-cryptocurrency-technologies-online-course/texts/893555-intro-to-crypto-and-cryptocurrencies
https://academy.b9lab.com/courses/B9lab/X16-0/2016/courseware/350259f977104a77a5708ac18c38824a/

Enterprise Blockchain Consortiums
http://bankinnovation.net/2017/03/enterprise-blockchain-consortiums-part-1/

Blockchain: A Distributed ledger
https://mastanbtc.github.io/blockchainnotes/blockchainintro/


What does $100 Ether mean?
https://medium.com/humanizing-the-singularity/what-does-ether-100-mean-bb58522f781e

Ethereum Growing Exponentially in China
https://medium.com/@andrewkeys_88339/ethereum-growing-exponentially-in-china-31f1d24c8ee9

https://medium.com/tag/ethereum

https://medium.com/tag/blockchain


How does the Blockchain Work (for Dummies) explained simply
https://medium.com/the-intrepid-review/how-does-the-blockchain-work-for-dummies-explained-simply-9f94d386e093


Blockchain Tokens and the dawn of the Decentralized Business Model
https://blog.coinbase.com/app-coins-and-the-dawn-of-the-decentralized-business-model-8b8c951e734f

How to Raise Money on a Blockchain with a Token
https://blog.gdax.com/how-to-raise-money-on-a-blockchain-with-a-token-510562c9cdfa

Blockchain: The Pro's and Con's of a Technology that Will Affect our Future
https://medium.com/totvslabs/blockchain-the-pros-and-con-s-of-a-technology-that-will-affect-our-future-f67037da7d64

Blockchain Can Revolutionize EHRs With Optimum Security and Interoperability 
https://dzone.com/articles/blockchain-can-revolutionize-ehrs-with-optimum-sec

Blockchain: Everything You Need to Know
https://dzone.com/articles/blockchain-everything-you-need-to-know?fromrel=true

Smart Contract Security: How to Never Break the Blockchain 
https://dzone.com/articles/smart-contract-security-how-to-never-break-the-blo?fromrel=true

Berlin, the Blockchain Capital of the World?
https://dzone.com/articles/berlin-the-blockchain-capital-of-the-world?fromrel=true

![](https://assets.weforum.org/editor/_6PsX2aYNmUhNu-lU7q8wx2AinuqblUEjM2GuQ1SFPs.png)
![](http://arch-doc.rchain.coop/en/latest/_images/comparison-table.png)

