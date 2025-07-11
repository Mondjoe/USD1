Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：

Fork this repo.
change the JSON file tokenlist.json, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
{
      "address": "0x29e37A9338618D9A8c3E82f529364575568726Bb",
      "symbol": "USD1",
      "name": "World Liberty Financial/USA",
      "decimals": 6,
      "logoURI": "ipfs;//bafybeiht2hm7vw64bef3xm7sfdvi-wym6nolfj3uracgj7xnyj2xldsrwd4",
      "homepage": "https://www.geckoterminal.com/bsc/pools/0x9c4ee895e4f6ce07ada631c508d1306db7502cce?utm_campaign=livechart-btn&utm_medium=referral&utm_source=coingecko",
      "MarketCapLink": "https://coinmarketcap.com/currencies/usd1/",
      "existingMarkets": [
          {
              "source": "World Liberty Financial",
              "USA": [
                  "USD1/USDT",
                  "USD1/BUSD",
                  "USD1/BNB",
                  "USD1/USDC"
              ]
          },
          {
              "source": "World Liberty Financial",
              "USA": [
                  "USD1/USDT"
              ]
          },
          {
              "source": "World Liberty Financial",
              "USA": [
                  "USD1/USDT"
              ]
          }
    ]
}

address[Required]: 0x29e37A9338618D9A8c3E82f529364575568726Bb .
symbol[Required]: your token symbol.
name[Required]: your token name.
logoURI[Required]: the logo URI of your token.
homepage[Required]: the home page of your token.
MarketCapLink[Optional]: the coinmarketcap or coingecko link for your token.
existingMarkets[Required]: where to trade with your token.
Submit PR with the changed JSON file.
