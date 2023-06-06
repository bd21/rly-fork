# CCTP Relayer

<img src="header.png" width="512px">

CCTP Relayer is a simple service which listens for events on Ethereum and forwards them to Noble.  It is meant to be used in conjunction Circle's Cross Chain Transfer Protocol.

With 1000 threads it can index ~700 blocks per second, or about a week's worth of blocks in 70 seconds.

Installation
```shell
...
```

Running the relayer
```shell
rly start --config ./config/example-config.yaml
```
