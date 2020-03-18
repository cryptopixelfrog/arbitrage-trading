# arbitrage-trading
Arbitrage Monitoring &amp; Trading 
This is based on [OrFeed](https://github.com/ProofSuite/OrFeed), and particularly the [basicArbExample](https://github.com/ProofSuite/OrFeed/tree/master/nodeJSAppExamples/basicArbExample%20). For now, this repo does not have Smart Contract yet, but it is actually executing on Ethereum main net, so Smart Contract address and ABI is hard coded. I will make update on this later.

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

## Expecting monitoring output
```
Getting price.
 SAI Buy price(Uniswap):  105525848942701202538
 SAI Sell price(Kyber):  104693800557743205396
Checking to see if we should execute for arb
Buy Price: 105525848942701200000
Sell Price: 104693800557743210000
No arbitriage
```
