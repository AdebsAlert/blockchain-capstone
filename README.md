# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

## Launch Ganache:
Run this command in separate terminal window

`npx ganache-cli -m "candy maple cake sugar pudding cream honey rich smooth crumble sweet treat"`

## Run truffle tests:

`npm install`

`cd eth-contracts`

`npx truffle test ./test/TestERC721Mintable.js`

`npx truffle test ./test/TestSquareVerifier.js`

`npx truffle test ./test/TestSolnSquareVerifier.js`


## Deploy contracts to Rinkeby network
Commands:

`export INFURA_KEY="<your_infura_key>"`

`export MNEMONIC="<metamask>"`

`export NETWORK="rinkeby"`

`truffle migrate --network rinkeby --reset`

Result: 
```
  Verifier: 0x1A78eBBb655e897814A8eac826DB131A6a146a3a
  SolnSquareVerifier: 0x31Dd04045D5df5c979E4aA53EbaEDAbc4170bA2b
```


## SolnSquareVerifier ABI

SolnSquareVerifier Contract ABI place  [here](https://github.com/adebsalert/blockchain-capstone/blob/master/eth-contracts/build/contracts/SolnSquareVerifier.json)


Tokens minted with [myetherwallet tool](https://www.myetherwallet.com/interface/interact-with-contract)


OpenSea Rinkeby marketplace [link](https://rinkeby.opensea.io/assets/niktokenname)


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
