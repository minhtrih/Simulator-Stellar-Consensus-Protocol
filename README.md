## Federated Byzantine Agreement System

This repository currently implements a simulation of the Federated Byzantine Agreement System (FBAS), which is part of the Stellar Consensus Protocol (SCP) by David Mazières. The network is emulated via a server and websockets, in practice the network layer will of course be different. All messages of all client are distributed to all clients via the server. The interface let's you choose quorum slices. Any node can start a new instance of FBAS on a topic, which it automatically votes yes for. Other nodes / clients participate by clicking on vote and select a choice. The clients will determine quorums and blocking sets to accept and confirm values.

If you want to understand the basics of FBAS please read our [Medium article](https://medium.com/tixlcurrency/federated-byzantine-agreement-system-and-tixl-c60254ea2439).

## Running locally

- `yarn` in both folders
- `yarn start` in both folders

In practice you will want to open more than one tab of the client to have multiple nodes running.
