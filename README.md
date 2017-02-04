###Ethereum BoilerPlate

####Solidity
Ethereum programs execute Ethereum Virtual Machine (EVM) code. Solidity is a javascript-like coding language which compiles to EVM.

####Truffle
```npm install -g truffle```
Truffle is maintained by Tim Coulter. It simplifies compiling, deploying, and maintaining your ethereum contracts.

####Infura (?)
Infura provides access to Ethereum Nodes via cloud instances, to listen for changes on the Ethereum network.

####TestRPC
```npm install -g testrpc```
TestRPC allows you to mock an ethereum node to test your contracts.

####Geth
Get Homebrew.
```brew tap ethereum/ethereum```
```brew install ethereum```

See instructions here for more details, and for other OS's:
https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum

####Web3
```npm install web3```
Web3 is a javascript library that lets you issue RPC commands to your Ethereum node/TestRPC instance.

####Setting up a Node
Browser solidity compiler
Web 3 and RPC commands

```truffle build```

```testrpc```

```truffle migrate```

break down testrpc outputs

```
sendTransaction

  Transaction: 0x3df1923a5e57c73579b4c01639f94e606f0d64ba8d56457feabfede58f930f68
  Contract created: 0xe0e2791bc0f411fbecac4856aa4d3eb868ad8689
  Gas usage: 0x0259f5
  Block Number: 0x01
  Block Time: Sat Feb 04 2017 14:05:42 GMT-0800 (PST)
```

