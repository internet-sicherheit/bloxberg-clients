## Introduction
These are docker-compose is a standalone Ethereum Client running in a docker Container. There is volume persistence for chain data to be saved.

## Instructions
1) Clone the repository
2) cd /geth-docker or /parity-docker
2) docker-compose up

There is a example Genesis Configuration file in reference to Bloxberg for Geth. But the current docker-compose doesn't utilize this. Since we are connecting remotely, it fetches the genesis information.

## Chains
Currently the Parity & Geth are configured to work with Bloxberg Network 

## Importing a Metamask key
Sadly, importing from Metamask only works using Geth as an intermediary: https://www.blog.nodrama.io/parity-private-key-import/ Another Option includes https://medium.com/@kacharlabhargav21/connecting-geth-to-metamask-fc2b2c89d9f9

## Additional Documentation
[Docker Readme from Ethereum](https://github.com/openethereum/wiki/blob/master/Docker.md)
