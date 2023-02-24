# `vvs`

## 📁 Connector Info

* Type: SPOT AMM DEX
* Folder: [/hummingbot/gateway/src/connectors/vvs](https://github.com/hummingbot/hummingbot/tree/master/gateway/src/connectors/vvs)
* Maintainer: [CoinAlpha](https://coinalpha.com)

## 🏆 Exchange Tier

![](https://img.shields.io/static/v1?label=Hummingbot&message=BRONZE&color=green)

Bronze exchange connectors have passed the Minimum Voting Power Threshold in the latest Poll and are included in each monthly release. They are not maintained by Hummingbot Foundation but may be maintained by a community member.

## ℹ️ Exchange Info

* Website: <https://vvs.finance/>
* CoinMarketCap: <https://coinmarketcap.com/currencies/vvs-finance/>
* CoinGecko: <https://www.coingecko.com/en/exchanges/vvs_finance>
* API docs: <https://github.com/vvs-finance/vvs-ui/tree/master/packages/vvs-swap-sdk>
* Fees:

## 🔑 Connection

1. Follow the instructions on [Setting up Gateway](/gateway/setup) to install the Gateway Docker container
2. Run `gateway connect vvs` and follow the prompts to add your wallet private key. Like all API and private keys in Hummingbot, this key is encrypted with your Hummingbot password.
3. Afterwards, run `create` to create an [AMM Arbitrage](/strategies/amm-arbitrage/) strategy between Sushiswap and a different exchange.
4. Run `start` to start the strategy!

## 📘 Additional Resources

See [Cronos](/gateway/chains/cronos) for more information about the default configuration settings and how to change them.
