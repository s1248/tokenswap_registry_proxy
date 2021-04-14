
**Buni** is an automated **portfolio manager**, **liquidity provider**, and **price sensor**.

Stores a registry of Balancer Pool addresses for a given token address pair. Pools can be sorted in order of liquidity and queried via view functions. Used in combination with the Exchange Proxy swaps can be sourced and exectured entirely on-chain.


## Setup
For interactions or contract deployments on public testnets / mainnet, put your private key in hardhat.config.js


## Install Dependencies
```
npx install
```

## Development

Most users will want to consume the ABI definitions for BFactory and BPool.

This project follows the standard hardhat project structure. 

```
npx hardhat compile   # Compile contracts
npx hardhat run scripts/deploy-proxy.js # Deploy contracts
```
 
