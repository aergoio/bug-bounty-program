# Hacking

## Introduction

The Aergo blockchain uses Lua as the language for smart contracts. The engine used is LuaJIT, but the Just-In-Time compilation is disabled. The contracts are compiled with the `aergoluac` command line tool and sent to the blockchain as bytecode. The LuaJIT version is 2.1.0-beta3.

[LuaJIT documentation](http://luajit.org/luajit.html)

[Lua documentation](https://www.lua.org/manual/5.1/)

The Aergo blockchain uses the Lua 5.1 version, but some features are disabled.

[Aergo Lua documentation](https://aergo.readthedocs.io/en/latest/smart-contracts/lua/index.html)


## Learning

The first step is to watch this video about how to write a simple smart contract:

[![Your First Smart Contract in Lua](https://img.youtube.com/vi/PWc_m544JtU/0.jpg)](https://www.youtube.com/watch?v=PWc_m544JtU)

And then this one to deploy it to the blockchain:

[![How To Deploy Your Smart Contract](https://img.youtube.com/vi/nVkxTAt08HE/0.jpg)](https://www.youtube.com/watch?v=nVkxTAt08HE)


## Aergo Tools

### Creating and Deploying Contracts

To create and deploy smart contracts easily, you can use the [Aergo IDE](https://ide.aergo.io/)

You can also compile the contracts locally with the `aergoluac` command line tool, which can be downloaded [here](https://github.com/aergoio/aergo/releases)

### Running a Local Server

The Aergo blockchain can be run locally with the `aergosvr` command line tool, downloadable on the same link above.

The Aergo blockchain can also be [run locally with Docker](https://aergo.readthedocs.io/en/2.2/running-node/quickstart.html?highlight=docker#using-docker)

### Interacting with the blockchain

On the web:

* The [Aergo Connect](https://chrome.google.com/webstore/detail/aergo-connect/iopigoikekfcpcapjlkcdlokheickhpc) browser extension
* The Aergo [Transaction Builder](https://tx-builder.aergo.io/)
* [Javascript](https://github.com/aergoio/herajs)

On the command line:

* The `aergocli` command line tool, downloadable on the GitHub releases link above.
(you can automate it with bash scripts. example [here](https://github.com/aergoio/aergo/blob/develop/tests/test-max-call-depth.sh))

Via your own application:

* [Node.js](https://github.com/aergoio/herajs)
* [Python](https://github.com/aergoio/herapy)
* [Java](https://github.com/aergoio/heraj)
* [C and C++](https://github.com/aergoio/libaergo)
* [Swift](https://github.com/aergoio/libaergo)
* [Ruby](https://github.com/aergoio/libaergo)
* [PHP](https://github.com/aergoio/heraphp)

### Blockchain Explorer

If you are using the testnet instead of a local server/network, you can use the Aergo blockchain explorer: [AergoScan](https://testnet.aergoscan.io/)


## Contact

If you have any problem, you can make technical questions on [Discord](https://discord.com/invite/YuPCCeH)
 
