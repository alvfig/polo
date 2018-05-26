# polo

A command line interface, CLI, to trade on the [Poloniex exchange](https://poloniex.com) through its RestFul API.

You can consult your balance and place orders on the exchange.

It is a Python script with support to both versions 2 and 3.

```console
$ polo help
Examples:

polo balance
polo summary                  # margin
polo tradable                 # margin
polo position BTC_ETH         # margin
polo long BTC_ETH 0.01981 10  # margin
polo short BTC_ETH 0.01981 10 # margin
polo close BTC_ETH            # margin
polo buy BTC_ETH 0.01981 10   # exchange
polo sell BTC_ETH 0.01981 10  # exchange
polo orders BTC_ETH
polo trades 40829005273
polo cancel 40829005273
polo move 40829005273 0.01981 [10]
polo transfer ETH 10 exchange margin
```

## Install Python 3
## Install Python 2

## Configure
Create a `settings.py` file and fill it with yours API key and secret. Use the `settings.py_template` as a model.

## Examples
