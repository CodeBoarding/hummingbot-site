# `quickswap`

## 📁 Connector Info

* Type: SPOT AMM DEX
* Folder: [/gateway/src/chains/polygon](https://github.com/hummingbot/hummingbot/tree/master/gateway/src/chains/polygon)
* Maintainer:

## 🏆 Exchange Tier

![](https://img.shields.io/static/v1?label=Hummingbot&message=BRONZE&color=green)

Bronze exchange connectors have passed the Minimum Voting Power Threshold in the latest Poll and are included in each monthly release. They are not maintained by Hummingbot Foundation but may be maintained by a community member.

## ℹ️ Exchange Info

* Website: <https://quickswap.exchange/>
* CoinMarketCap: <https://coinmarketcap.com/exchanges/quickswap/>
* CoinGecko: <https://www.coingecko.com/en/exchanges/quickswap>
* API docs: <https://docs.quickswap.exchange/reference/>
* Fees:  <https://docs.quickswap.exchange>

## 🔑 Setup

1. Follow the instructions on [Setting up Gateway](/gateway/setup) to install the Gateway Docker container
2. Run `gateway connect quickswap` and follow the prompts to add your wallet private key. Like all API and private keys in Hummingbot, this key is encrypted with your Hummingbot password.
3. Afterwards, run `create` to create an [AMM Arbitrage](/strategies/amm-arbitrage/) strategy between Quickswap and a different exchange.
4. Run `start` to start the strategy!

## 📘 Additional Resources

See [Polygon](/gateway/chains/ethereum/#polygon) for more information about the default configuration settings and how to change them.
