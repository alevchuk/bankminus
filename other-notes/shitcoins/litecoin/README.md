
# Update: 2019-09-06

LTC does not have a discoverable testnet (no DNS seed) https://github.com/lightningnetwork/lnd/issues/1542
 https://github.com/lightningnetwork/lnd/issues/1860
 
And it's LND mainnet is tiny https://ltc.roska.life/


# Archive before 2019-09-06

# Litecoin

Testnet on Bitcoin is having issues (my faviourite faucet shutdown citing high fees https://testnet.coinfaucet.eu/en/).

> Testnet network is now experiencing a big transaction flood. Transactions fees are too high, so the faucet was temporarily closed.

> All of our transactions are stucked in unconfirmed transactions, when the situation improves, we will be back again.

So, at least for now, I'm switching to testing LND with Litecoin.


Also it will be easier to get bootstrapped on Litecoin mainnet because the fees are ~0.10 USD per transaction and chain size is 10x smaller (currently 18.95 GB on Litecoin vs 213.10 GB on Bitcoin).

LND supports two implementations of Litcoin full node: 
1. **litecoind**
2. **ltcd**

Currently I'm using **ltcd** because it's easier to build and litecoind has an issue when starting up: https://github.com/lightningnetwork/lnd/issues/1854
