## Introduction
This is a standalone Geth Client running in a docker Container. There is volume persistence for chain data to be saved.

## Instructions
1) Clone the repository
2) docker-compose up

There is a example Genesis Configuration file in reference to Bloxberg. But the current docker-compose doesn't utilize this. Since we are connecting remotely, it fetches the genesis information.

## Chains
Currently the Geth is configured to work with Bloxberg Network 

## Importing a Metamask key
Sadly, importing from Metamask only works using Geth as an intermediary: https://www.blog.nodrama.io/parity-private-key-import/ Another Option includes https://medium.com/@kacharlabhargav21/connecting-geth-to-metamask-fc2b2c89d9f9

## Security Consideration
The Docker Container exposes the following port ports <br/>
8545 - JSON RPC <br/>


## Additional Documentation
[Docker Readme from Ethereum](https://github.com/openethereum/wiki/blob/master/Docker.md)
