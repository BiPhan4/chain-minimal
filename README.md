This is a clone and extension of minid, which was developed by the cosmos registry and can be found here: 

https://github.com/cosmosregistry/chain-minimal

This repo serves as a dev sandbox for the jackal protocol.

We thank the chain registry team for creating minid <3 

# Mini - A minimal Cosmos SDK chain

This repository contains an example of a tiny, but working Cosmos SDK chain.
It uses the least modules possible and is intended to be used as a starting point for building your own chain, without all the boilerplate that other tools generate. It is a simpler version of Cosmos SDK's [simapp](https://github.com/cosmos/cosmos-sdk/tree/main/simapp).

`Minid` uses the **latest** version of the [Cosmos-SDK](https://github.com/cosmos/cosmos-sdk).

## How to use

In addition to learn how to build a chain thanks to `minid`, you can as well directly run `minid`.

### Installation

Install and run `minid`:

```sh
git clone git@github.com:cosmosregistry/chain-minimal.git
cd chain-minimal
make install # install the minid binary
make init # initialize the chain
minid start # start the chain
```

## Useful links

* [Cosmos-SDK Documentation](https://docs.cosmos.network/)
