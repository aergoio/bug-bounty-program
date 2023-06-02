# Hacking

## Introduction

The Aergo blockchain uses Lua as the language for smart contracts. The engine used is LuaJIT, but the Just-In-Time compilation is disabled. The contracts are compiled with the `aergoluac` command line tool and sent to the blockchain as bytecode. The LuaJIT version is 2.1.0-beta3.

[LuaJIT documentation](http://luajit.org/luajit.html)

[Lua documentation](https://www.lua.org/manual/5.1/)

The Aergo blockchain uses the Lua 5.1 version, but some features are disabled.

[Aergo Lua documentation](https://aergo.readthedocs.io/en/latest/smart-contracts/lua/index.html)


## Learning

The first step is to watch [this video](https://www.youtube.com/watch?v=PWc_m544JtU) about how to write a simple smart contract

And then [this video](https://www.youtube.com/watch?v=nVkxTAt08HE) to deploy it to the blockchain


## Aergo Tools

To create and deploy smart contracts easily, you can use the [Aergo IDE](https://ide.aergo.io/)

You can also compile the contracts locally with the `aergoluac` command line tool, which can be downloaded [here](https://github.com/aergoio/aergo/releases)

The Aergo blockchain can be run locally with the `aergosvr` command line tool, downloadable on the same link above.

The Aergo blockchain can also be [run locally with Docker](https://aergo.readthedocs.io/en/2.2/running-node/quickstart.html?highlight=docker#using-docker)

To interact with the blockchain, you can use:

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


The Aergo blockchain explorer is [AergoScan](https://testnet.aergoscan.io/)
