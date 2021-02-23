
<div align="center">
  <a href="https://www.fusion.org/"><img width="250px" src="./project_logo.png">
  </a><br />
  <a href="https://www.fusion.org/">Fusion</a> is an open source blockchain-based connected ecosystem for financial transactions.
  <br />Fusion's unique Time-Lock feature enables you to extract time-value out of your digital assets and easily model time-based transaction on the blockchain.
</div>


Pull requests are welcome!

## Contents

- [Documentation](#documentation)
- [Staking](#staking)
- [Wallets](#wallets)
- [Explorers](#explorers)
- [Network monitoring](#network-monitoring)
- [Programming](#programming)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Dapps](#dapps)
- [Interfaces](#interfaces)
- [Network gateways](#network-gateways)
- [Community](#community)
- [Misc](#misc)
- [Official](#official)

## Documentation

- [Whitepaper](https://uploads-ssl.webflow.com/5cbf7269aa4c8ec895500d90/5cd19865da79bd05684babfc_Fusion%20White%20Paper.pdf) - An outline of the Fusion vision and protocol architecture.
- [DCRM yellow paper](https://uploads-ssl.webflow.com/5cbf7269aa4c8ec895500d90/5cd19874373c9579f4d9b6ee_DCRM%20Yellow%20Paper.pdf) - A technical paper on Distributed Private Key Control (DCRM), one of the key Fusion features.
- [Fusion RPC API](https://github.com/FUSIONFoundation/efsn/wiki/FSN-RPC-API) - Fusion RPC API reference.
- [Fusion API](https://fusionapi.readthedocs.io/en/latest/) - Fusion API reference.
- [web3-fusion-extend](https://web3-fusion-extend.readthedocs.io/) - A collection of Fusion JavaScript API libraries.
- [web3fsnpy](https://web3fsnpy.readthedocs.io/en/latest/) - A Python library for interacting with Fusion.

## Staking

### Calculators

- [Fusion staking calculator](https://fusionstaking.com/) - A staking calculator.

### Pools

- [FSNPOOL](https://fsnpool.com/)
- [GOFSN](https://gofsn.com/)
- [NodeNetworks Fusion pool](https://www.nodenetworks.org/fsnpool/)
- [PoolTogether](https://pooltogether.io/)

## Wallets

- [MyFusionWallet](https://www.myfusionwallet.com/) - Official Fusion web wallet.
- [Whallet](https://whallet.net/) - An online Fusion wallet that supports Ledger and Trezor.

## Explorers

- [Fusion block explorer](https://blocks.fusionnetwork.io/) - Official Fusion block explorer.
- [FSN 365](https://www.fsn365.com/) - Another Fusion block explorer.
- [FSNEXplorer](https://fsnex.com/) - Another Fusion block explorer.

## Network monitoring

### Mainnet

- [FUSIONMINING](https://fusionmining.org/) - Comprehensive main network stats.
- [Mainnet node monitor](http://stats.fusionnetwork.io/) - Fusion mainnet node monitor.

### Testnet

- [Testnet node monitor](http://devnodestats.fusionnetwork.io/) - Fusion testnet node monitor.

## Programming

- [Fusion testnet faucet](https://fsn.dev/faucet/) - A faucet for testnet FSN.
- [web3-fusion-extend](https://www.npmjs.com/package/web3-fusion-extend) - Fusion JavaScript API to the blockchain.
- [web3fsnpy](https://github.com/FUSIONFoundation/web3fsnpy) - Fusion Python API to the blockchain.

## Tools

- [Truffle](https://github.com/FUSIONFoundation/efsn/wiki/Deploy-smart-contract-using-truffle) - A how-to to compile and deploy a smart contract with [Truffle](https://www.trufflesuite.com/).
- [Remix IDE](https://github.com/FUSIONFoundation/efsn/wiki/Deploy-smart-contract-using-remix) - A how-to to compile and deploy a smart contract with [Remix IDE](https://remix.ethereum.org/).
- [solc](https://github.com/FUSIONFoundation/efsn/wiki/Deploy-smart-contract-using-solc) - A how-to to compile and deploy a smart contract with [solc](https://solidity.readthedocs.io/en/v0.5.3/installing-solidity.html).
- [FsnNodeHealthCheck](https://github.com/marcelcure/FsnNodeHealthCheck) - An ligthweight tool that runs in the background and monitors your Fusion node.
- [TxnsScript](https://github.com/katesroad/TxnsScript) - An open-source script to track transactions, addresses, and balances.

## Tutorials

- [Official Fusion guides](https://fusionnetworks.zendesk.com/hc/en-us) - A collection of official guides.
- [Community Fusion guides](https://fusionmining.org/guides) - A collection of guides from [FUSIONMINING](https://fusionmining.org/).

## Videos

- [NodeNetworks pool on YouTube](https://www.youtube.com/channel/UCws1m7Z3LtOBJsQckNsjguA) - Fusion-related videos from the [NodeNetworks pool](https://www.nodenetworks.org/fsnpool/).

## Dapps

- [Chainge](https://chainge.finance/) - A decentralized finance dapp.
- [Anyswap](https://anyswap.exchange/) - A decentralized exchange where you can trade not just ERC-20 tokens, but coins and tokens from any other blockchain protocols, including Ethereum and Bitcoin.

## Interfaces

Various public APIs.

### Block Explorer
Note: See [here](https://github.com/FUSIONFoundation/web3-fusion-extend/tree/master/examples/blockexplorerapi), used by the [official block explorer](https://blocks.fusionnetwork.io) and MyFusionWallet.

#### Official
- Mainnet:
  - Endpoint: `https://api.fusionnetwork.io`
- Testnet:
  - Endpoint: `https://testnetapi.fusionnetwork.io`
  
#### Community
- Mainnet:
  - Endpoint: `n/a`

### FSNEX Stats
- Mainnet:
  - Endpoints:
    - Network: `https://api.fsnex.com/network`
    - Blocks: `https://api.fsnex.com/chart/block`
    - Activity: `https://api.fsnex.com/chart/tx`
    - Addresses: `https://api.fsnex.com/chart/add`
    - Transfers: `https://api.fsnex.com/chart/sends`
    - Supply: `https://api.fsnex.com/supply`

## Network gateways

Public RPC gateways.

### HTTP

#### Community:
- Mainnet gateway (FOSC):
  - Endpoint: `https://fsn.dev/api`
  - Chain ID: `32659`
- Testnet gateway (FOSC):
  - Endpoint: `https://testnet.fsn.dev/api`
  - Chain ID: `46688`

#### Anyswap:
- Mainnet gateway:
  - Endpoint: `https://mainnet.anyswap.exchange`
  - Chain ID: `32659`
- Testnet gateway:
  - Endpoint: `https://testnet.anyswap.exchange`
  - Chain ID: `46688`

### WebSocket

#### Official:
- Mainnet gateway:
  - Endpoint: `wss://mainnetpublicgateway1.fusionnetwork.io:10001`
  - Chain ID: `32659`
- Testnet gateway:
  - Endpoint: `wss://testnetpublicgateway1.fusionnetwork.io:10001`
  - Chain ID: `46688`

#### Community:
- Mainnet gateway:
  - Endpoint: `n/a`
  - Chain ID: `32659`

## Community

- [Fusion Open Source community website](https://fsn.dev/) - A website for the Fusion open source community (FOSC).
- [FOSC GitHub](https://github.com/fsn-dev) - A FOSC GitHub organization.
- [Fusion official community in Telegram](https://t.me/FUSIONFoundation) - An official Telegram community.
- [Fusion developer community in Telegram](https://t.me/FsnDevCommunity) - A developer Telegram community.
- [Fusion trading community in Telegram](https://t.me/FusionTrading) - A trading Telegram community.
- [Fusion Russian community in Telegram](https://t.me/fusion_ru) - A Russian Telegram community.
- [Fusion on Reddit](https://www.reddit.com/r/FusionFoundation) - A Fusion Reddit community.

## Misc

- [FSN FEED](https://fsnfeed.com/) - A news feed for all things Fusion.

## Official

- [Fusion website](https://www.fusion.org/)
- [Fusion on Medium](https://medium.com/@fusionprotocol/)
- [Fusion Twitter](https://twitter.com/FUSIONProtocol/)
- [Fusion on YouTube](https://www.youtube.com/channel/UCVZ_1c6x7jRlOs4g2hMZZMQ)

## Contribute

Contributions are welcome! Read [contribution guidelines](CONTRIBUTING.md).
