---
tags:
- amm exchange connector
- avalanche dex
---

# `pangolin`

The Pangolin connector in [Gateway](/gateway) is responsible for all on-chain operations (e.g. fetching prices and creating swap transactions).

It interfaces with the [`GatewayEVMAMM`](https://github.com/hummingbot/hummingbot/blob/master/hummingbot/connector/gateway_EVM_AMM.py) class in the Hummingbot client, which is responsible for interfacing with all EVM-based Gateway AMMs.

## 📁 [Connector folder](https://github.com/hummingbot/hummingbot/tree/master/gateway/src/connectors/pangolin)

## ℹ️ Exchange Info

**Pangolin**
[Website](https://pangolin.exchange/) | [CoinMarketCap](https://coinmarketcap.com/exchanges/pangolin/) | [CoinGecko](https://www.coingecko.com/en/exchanges/pangolin)

* API docs: <https://github.com/pangolindex/pangolin-api>
* SDK: <https://github.com/pangolindex/sdk>
* FAQ: <https://pangolin.exchange/faq/>

## 🔗 Supported Chains

* [Avalanche](/gateway/chains/ethereum/#avalanche)

## 👷 Developer

Added by CoinAlpha in [v1.4.0](/release-notes/1.4.0/)

## 🔑 Setup

1. Follow the instructions on [Setting up Gateway](/gateway/setup) to install the Gateway Docker container, but **DO NOT** run `gateway connect pangolin` yet.
2. Run `gateway config avalanche.networks.avalanche.nodeURL` and enter your desired Node RPC provider or use the default. If using fuji, run `gateway config avalanche.networks.fuji.nodeURL` and enter your desired Node RPC provider.
3. Now, run `gateway connect pangolin` and add your Avalanche wallet private key. Like all API and private keys in Hummingbot, this key is encrypted with your Hummingbot password.
4. Afterwards, run `create` to create an [AMM Arbitrage](/strategies/amm-arbitrage/) strategy between Pangolin and a different exchange.
5. Run `start` to start the strategy, and you're trading!

## 📘 Additional Resources

* We recommend using Infura for the RPC node link. Here's a quick guide on how to create the project and get the link - <https://blog.infura.io/post/getting-started-with-infura-28e41844cc89>
* If for some reason you prefer to use a different provider instead of Infura here's a list of the top ones - <https://github.com/arddluma/awesome-list-rpc-nodes-providers#ethereum>
* [RPC.Info](https://rpc.info/) has a list that users can use for testnets and other RPC nodes
