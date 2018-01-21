# Welcome to Blockchain.Ethereum
Simple web application interacting with the Ethereum network, meant to become a DAPP as soon as I'll introduce smart contracts.

For the time being its key features are:
  - Connection to the Ethereum Network via a node running on localhost.
  - Transfer funds between wallet accounts.
  - Transaction monitoring.

I've set up my Ethereum local environment as follows:
  - Run a full node by geth on the localhost and created two accounts.
  - For the sake of experimenting, I've installed an ethereum wallet UI, which I then connected to the above node.
  - Created two accounts by the geth command line and got them some Ethers on the Rinkeby testnet, https://faucet.rinkeby.io/. 
  - Fully synchronized on both main and testnets but connected the web application to the testnet only.
  
## Development environment and tools
- Ubuntu 16.04.3 LTS.
- Eclipse Neon.
- JBoss Wildfly 10.1.

## Roadmap

1. Add a back end to the web application, possibly NoSQL.
2. Add smart contracts.
