# arbitrage-trading
Arbitrage Monitoring &amp; Trading 

## Checking out repo and install packages
```
  git clone https://github.com/cryptopixelfrog/arbitrage-trading.git
  cd arbitrage-trading
  npm install
```
## Create .evn file and add neccessary info
```
  touch .env
  vim .env
```
Add those in .env
```
TRADERWALLETADDR=
WALLETPRIVATEKEY=
INFURAAPIKEY=
```
This is not neccessary for monitoring, but only need for actual trading.

## Run the index.js
```
  cd arbitrage-trading
  npm start
```

## Expecting output
```
Getting price.
 SAI Buy price(Uniswap):  105525848942701202538
 SAI Sell price(Kyber):  104693800557743205396
Checking to see if we should execute for arb
Buy Price: 105525848942701200000
Sell Price: 104693800557743210000
No arbitriage
```
