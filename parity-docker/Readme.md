## Introduction
This is a standalone Geth Client running in a docker Container. There is volume persistence for chain data to be saved.

## Instructions
1) Clone the repository
2) docker-compose up

## Other Chains
The Docker Compose command section lets you choose the chain you want to sync with
```ropsten``` ```kovan``` ```mainnet```

## Pairty Images
You can change the Image you need in Parity
Options for the [Docker Image Tag](https://hub.docker.com/r/parity/parity)

## Importing a Metamask key
Sadly, importing from Metamask only works using Geth as an intermediary: https://www.blog.nodrama.io/parity-private-key-import/


## Security Consideration
The Docker Container exposes multiple ports <br/>
8545 - JSON RPC <br/>
8546 - Websockets RPC <br/>
30303/tcp & 30303/udp - TCP Node listening port and UDP discovery port.

## Additional Documentation
[Docker Readme from Ethereum](https://github.com/openethereum/wiki/blob/master/Docker.md)

## Todo
1) Check compatibilty with other ethereum clients (geth)