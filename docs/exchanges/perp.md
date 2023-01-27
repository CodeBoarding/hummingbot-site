# `perp`

## 📁 Connector Info

* Type: PERP AMM DEX
* Folder: [/gateway/src/connectors/perp](https://github.com/hummingbot/hummingbot/tree/master/gateway/src/connectors/perp)
* Configs: [/gateway/src/templates/perp.yml](https://github.com/hummingbot/hummingbot/blob/master/gateway/src/templates/perp.yml)
* Maintainer: None

## 🏆 Exchange Tier

![](https://img.shields.io/static/v1?label=Hummingbot&message=BRONZE&color=green)

Bronze exchange connectors have passed the Minimum Voting Power Threshold in the latest Poll and are included in each monthly release. They are not maintained by Hummingbot Foundation but may be maintained by a community member.

## ℹ️ Exchange Info

* Website: https://perp.com/
* CoinMarketCap](https://coinmarketcap.com/exchanges/perpetual-protocol/
* CoinGecko: https://www.coingecko.com/en/exchanges/perpetual_protocol
* API docs: <https://perp.com/developers>
* SDK: <https://github.com/perpetual-protocol/sdk-curie>

## 🕸️ Supported Chains and Networks

* Ethereum: `optimism`

## 🔑 Connection

```
Which chain do you want uniswap to connect to? (ethereum, polygon) >>>
Which network do you want uniswap to connect to? (mainnet, goerli, arbitrum_one) >>>
Enter your ethereum-mainnet private key >>>>
```

If connection is successful:
```
The uniswap connector now uses wallet [pubKey] on ethereum-mainnet
```

**Liquidity provision:** The  `uniswapLP` connector interfaces with liquidity provision-related functions. Run `gateway connect uniswapLP` in order to connect your wallet to perform LP functions.