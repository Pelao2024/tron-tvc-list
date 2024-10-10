# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t
      "symbol": usdt
      "name": usdttoken
      "decimals": 6,
      "logoURI": "https://coin.top/profile_images/JKtJTydD_400x400.jpg",
      "homepage": "https://usdtlink.org/",
      "MarketCapLink": "https://coinmarketcap.com/currencies/usdtlink/",
      "existingMarkets": [
          {
              "source": "Binance",
              "pairs": [
                  "tron/USDT",
                  "tron/BUSD",
                  "tron/BNB",
                  "tron/USDC"
              ]
          },
          {
              "source": "tether",
              "pairs": [
                  "tron/USDT"
              ]
          },
          {
              "source": "metamask",
              "pairs": [
                  "tron/USDT"
              ]
          }
    ]
}
```
* `address`[TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t]: your token address.
* `symbol`[usdt]: your token symbol.
* `name`[usdttoken]: your token name.
* `logoURI`[https://coin.top/profile_images/JKtJTydD_400x400.jpg]: the logo URI of your token.
* `homepage`[https://usdtlink.org/]: the home page of your token.
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Binance]: where to trade with your token.
3) Submit PR with the changed JSON file.


