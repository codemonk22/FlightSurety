# FlightSurety - Oracle Blockchain DApp


## FlightSurety is an oracle blockchain dapp for flight delay insurance for passengers.

### Install

This repository contains Smart Contract code in Solidity (using Truffle), tests (also using Truffle), dApp scaffolding (using HTML, CSS and JS) and server app scaffolding.

To install, download or clone the repo, then:

`npm install`
`truffle compile`

```
┌──(blockchain05㉿bcdev05)-[~/workspace/FlightSurety]
└─$ ganache-cli --p 8545 --mnemonic "candy maple velvet cake sugar cream honey rich smooth crumble sweet treat"
ganache v7.2.0 (@ganache/cli: 0.3.0, @ganache/core: 0.3.0)
Starting RPC server

Available Accounts
==================
(0) 0x47Adc0faA4f6Eb42b499187317949eD99E77EE85 (1000 ETH)
(1) 0x4ef9E4721BBF02b84D0E73822EE4E26e95076b9D (1000 ETH)
(2) 0x4a5A6460D00c4D8C2835A3067f53Fb42021D5bB9 (1000 ETH)
(3) 0x4222EC932c5a68b80e71F4dDebb069fa02518b8A (1000 ETH)
(4) 0x2Da061c6cFA5C23828e9D8dfbe295a22e8779712 (1000 ETH)
(5) 0xc1f061d629bBbA139DbD07F2eb6A9252a45514C7 (1000 ETH)
(6) 0xF8e160be646D2429C64D46Fba8e8588b8483DBaF (1000 ETH)
(7) 0x74260Eb42FfDe3C442682C4fb6CEB3e801bBB79A (1000 ETH)
(8) 0x76393AD6569272385963Bc9A135356456bBe3F83 (1000 ETH)
(9) 0xae1708B0aF10BF1FBeE6B4b4220D9453f6007eeB (1000 ETH)

Private Keys
==================
(0) 0xeffa7c6816819ee330bc91f1623f3c66a9fed268ecd5b805a002452075b26c0b
(1) 0x258b7f85027d7b20f74ecfbfca556aad8eff933365fe5b7473355040c09db418
(2) 0x09288ce70513941f8a859361aeb243c56d5b7a653c1c68374a70385612fe0c2a
(3) 0x6ccfcaa51011057276ef4f574a3186c1411d256e4d7731bdf8743f34e608d1d1
(4) 0x60090a13d72f682c03db585bf6c3a296600b5d50598a9ceef3291534dede6bea
(5) 0xe25f43772b0d8f19b0a768dfa779ec2f1422241dfe75293de879dc76607b0405
(6) 0x5644e113a0db2e89243741a31dfae322a20c09cc0025826288bf37725464ce34
(7) 0xc053485e0b1e5611a8e9368ca4d9400a62dade4e7abfdaea93f46c382ec82d1d
(8) 0x862d035b908235f1d0af51713a9e6fc8a1108ac98a77a0be91131d226aa8f4d0
(9) 0x7381f9ee53c41bde0d83e2e69a39f9ddfab74da872d653271a2a9ba050670583

HD Wallet
==================
Mnemonic:      candy maple velvet cake sugar cream honey rich smooth crumble sweet treat
Base HD Path:  m/44'/60'/0'/0/{account_index}

Default Gas Price
==================
2000000000

BlockGas Limit
==================
30000000

Call Gas Limit
==================
50000000

Chain Id
==================
1337

RPC Listening on 127.0.0.1:8545
eth_blockNumber
eth_blockNumber
net_version
net_version
eth_accounts
eth_accounts
eth_accounts
eth_getBlockByNumber
eth_accounts
net_version
(node:90591) MaxListenersExceededWarning: Possible EventEmitter memory leak detected. 11 close listeners added to [Server]. Use emitter.setMaxListeners() to increase limit
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x138975d6b7635b71f4dc429d68e9619eea7d95c0e7188f37f7b31a33918d4e35
  Contract created: 0xee08e5e6643952b3cb22642d2a04a2992141eddd
  Gas usage: 226537
  Block number: 1
  Block time: Mon May 30 2022 17:15:17 GMT-0500 (Central Daylight Time)

eth_getTransactionReceipt
eth_getCode
eth_getBlockByNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x228cafef4f050c450968b65d263ef7d636958a8681803482cbe3f31a8e99d030
  Gas usage: 45763
  Block number: 2
  Block time: Mon May 30 2022 17:15:17 GMT-0500 (Central Daylight Time)

eth_getTransactionReceipt
eth_getBlockByNumber
eth_accounts
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0xd86e53685f01fb4a8ab0300687c57c6ec74a602e86afa3af381804503fbffb35
  Contract created: 0xce33f6257e24958ffc018076befd1893f762f68c
  Gas usage: 212082
  Block number: 3
  Block time: Mon May 30 2022 17:15:17 GMT-0500 (Central Daylight Time)

eth_getTransactionReceipt
eth_getCode
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x2e554bb685a826f595fc54ad3177270f2007356956fbd35ac7551de8fb9c3d2e
  Contract created: 0xddff46dc8686cc18c40489e56b2443a897ed6bd8
  Gas usage: 1004541
  Block number: 4
  Block time: Mon May 30 2022 17:15:17 GMT-0500 (Central Daylight Time)

eth_getTransactionReceipt
eth_getCode
eth_getBlockByNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x1e3e0bb5bb2004dab4ff8b6b78b56c33c2200a325ca0b72981888fc152da3153
  Gas usage: 28663
  Block number: 5
  Block time: Mon May 30 2022 17:15:17 GMT-0500 (Central Daylight Time)

eth_getTransactionReceipt
eth_blockNumber
eth_blockNumber
net_version
net_version
eth_accounts
eth_accounts
eth_accounts
eth_getBlockByNumber
eth_accounts
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x67093a65b2d91882c33e95575ea1041838615aad4027ba99fb1e0f0be3b7aedd
  Contract created: 0x06d590f2b2a246d2abdb7b2a793f634769dad711
  Gas usage: 226537
  Block number: 6
  Block time: Mon May 30 2022 17:17:06 GMT-0500 (Central Daylight Time)

```


## Develop Client


To run truffle tests:

`truffle test ./test/flightSurety.js`
`truffle test ./test/oracles.js`

![Activity diagram](/images/WholeScreen01.png)




To use the dapp:

`truffle migrate`

![Activity diagram](/images/truff-mig01.png)
![Activity diagram](/images/truff-mig02.png)

`npm run dapp`

![Activity diagram](/images/run_dapp01.png)

To view dapp:

`http://localhost:8000`

![Activity diagram](/images/WebSite-01.png)


## Develop Server

`npm run server`

![Activity diagram](/images/npm_run_ser01.png)
![Activity diagram](/images/npm_run_ser02.png)

`truffle test ./test/oracles.js`

![Activity diagram](/images/truff_oracle.png)


 ` dapp and server config file with ganache account details `
 
![Activity diagram](/images/dapp_config.png)
![Activity diagram](/images/server_config.png)


## Deploy

To build dapp for prod:
`npm run dapp:prod`

![Activity diagram](/images/dapp-prod-01.png)
![Activity diagram](/images/dapp-prod-02.png)

Deploy the contents of the ./dapp folder

## Resources

* [How does Ethereum work anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)
* [BIP39 Mnemonic Generator](https://iancoleman.io/bip39/)
* [Truffle Framework](http://truffleframework.com/)
* [Ganache Local Blockchain](http://truffleframework.com/ganache/)
* [Remix Solidity IDE](https://remix.ethereum.org/)
* [Solidity Language Reference](http://solidity.readthedocs.io/en/v0.4.24/)
* [Ethereum Blockchain Explorer](https://etherscan.io/)
* [Web3Js Reference](https://github.com/ethereum/wiki/wiki/JavaScript-API)
