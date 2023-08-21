## 🛠 Connector Info

- **Exchange Type**: Centralized Exchange (**CEX**)
- **Market Type**: Central Limit Order Book (**CLOB**)
- **Maintenance Tier**: ![](https://img.shields.io/static/v1?label=Hummingbot&message=BRONZE&color=green)
- **Maintainer**: [CoinAlpha](https://coinalpha.com)

Currently, Bit Perpetual is a **Bronze** exchange, as voted by HBOT holders in each quarterly [Epoch](/governance/epochs). This means Hummingbot Foundation does not maintain the components below, but community members may submit [Proposals](/governance/proposals) to fund development bounties and approve pull requests to fix bugs and add enhancements to them.

| Component | Status | Notes | 
| --------- | ------ | ----- |
| [🔀 Spot Connector](#spot-connector) | Not available |
| [🔀 Perp Connector](#perp-connector) | ✅ |
| [🕯 Spot Candles Feed](#spot-candles-feed) | Not built  | 
| [🕯 Perp Candles Feed](#perp-candles-feed) | Not built  | 

## ℹ️ Exchange Info

- **Website**: <https://www.bit.com>
- **CoinMarketCap**: <https://coinmarketcap.com/exchanges/bit-com/>
- **CoinGecko**: <https://www.coingecko.com/en/exchanges/bit_futures>
- **API Docs**: <https://www.bit.com/docs/en-us/linear_futures.html>
- **Fees**: <https://helpcenter.bit.com/hc/en-us/articles/10740865746969-1-How-much-is-Spot-Trading-Fees->
- **Supported Countries**: Not available

## 🔑 How to Connect

### Generate API Keys

### Add Keys to Hummingbot

From inside the Hummingbot client, run `connect bitcom_perpetual`:

```
Enter your bit_com_perpetual API key >>>
Enter your bit_com_perpetual secret key >>>
Enter your bit_com_perpetual user id >>>
```

If connection is successful:

```
You are now connected to bit_com_perpetual
```
## 🔀 Perp Connector
*Integration to spot markets API endpoints*

- **ID**: `bit_com_perpetual`
- **Connection Type**: WebSocket
- **Folder**: <https://github.com/hummingbot/hummingbot/tree/master/hummingbot/connector/derivative/bit_com_perpetual>

### Order Types

This connector supports the following `OrderType` constants:

- `LIMIT`
- `MARKET`

### Paper Trading
```

Note: I've replaced the URLs and other references to "Bitget" with "Bit-com". If there are specific URLs or other details for Bit-com that differ from the ones provided, you'll need to update them accordingly.