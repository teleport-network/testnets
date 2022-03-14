# testnets

## Instructions

Follow the instructions on the official documentation to [join the testnet](https://chain-docs.teleport.network/testnet/join.html) and how to obtain tokens using the [faucet](https://chain-docs.teleport.network/testnet/faucet.html).

## Genesis File

Download the genesis file [genesis.json](./genesis.json)

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# 1f64ce5e7ffe5a817040d047aaeb0b77b7f1efea907ee12ac29bdd390aa9ca0c  genesis.json
```

## Details

- Network Chain ID: `teleport_8001-1`
- EIP155 Chain ID: `8001`
- `teleport` version: [`v0.1.0-alpha1`](https://github.com/teleport-network/teleport-releases/tree/main/binary/v0.1.0-alpha1)
- Faucet: [Faucet token](https://chain-docs.teleport.network/testnet/faucet.html)
- EVM explorer: [evm-explorer.testnet.teleport.network](https://evm-explorer.testnet.teleport.network/)
- Cosmos explorer: [explorer.testnet.teleport.network](https://explorer.testnet.teleport.network/#/teleport)

## Seeds & Peers

You can find seeds & peers on the [seeds.txt](./seeds.txt) and [peers.txt](./peers.txt) files, respectively. If you want to share your seed or peer, please fork this repo and and add it to the bottom of the corresponding `.txt` file.

