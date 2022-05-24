# A React.js Application Detailing The Top 50 Cryptoassets At Any Given Time
A cryptocurrency price tracker application made w/ React & Axios.

As shown in the images below, you can navigate between each of the top 50 cryptoassets at any given moment - all metrics are updated regularly through CoinGecko's API.
<img width="1440" alt="Main Page" src="https://user-images.githubusercontent.com/98287394/170054662-e5c3efe2-aea1-4eee-be82-0049dec62fe7.png">

Hover over and click on a coin to select it...
And it will navigate you to a further page, giving more intricate details and a brief description of the cryptoasset and what it sets about achieving.
<img width="1440" alt="Page 2" src="https://user-images.githubusercontent.com/98287394/170054802-a9030176-5fc2-4eab-a51a-4bf1b0b989ed.png">

Prices are shown in USD, as that is the most liquid fiat currency in cryptocurrency trading.

API Link: https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=50&page=1&sparkline=false
