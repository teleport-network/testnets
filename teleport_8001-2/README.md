# Teleport_8001-2

## Instructions

Follow the instructions on the official documentation to [join the testnet](https://chain-docs.teleport.network/testnet/join.html) and how to obtain tokens using the [faucet](https://chain-docs.teleport.network/testnet/faucet.html).

## Genesis File

Download the genesis file [genesis.json](./genesis.json)

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# afec694105c09a9e12beaa4e513ca7464d7bcaf89ad08a4452b79eb15026478a  genesis.json
```

## Details

- Network Chain ID: `teleport_8001-2`
- EIP155 Chain ID: `8001`
- `teleport` version: [`v0.1.0`](https://github.com/teleport-network/teleport-releases/tree/main/binary/v0.1.0)
- Faucet: [Faucet token](https://chain-docs.teleport.network/testnet/faucet.html)
- EVM explorer: [evm-explorer.testnet.teleport.network](https://evm-explorer.testnet.teleport.network/)
- Cosmos explorer: [explorer.testnet.teleport.network](https://explorer.testnet.teleport.network/#/teleport)

### Public Endpoints

**EVM RPC Endpoints:**

* https://evm-rpc.testnet.teleport.network
* https://evm-rpc0.testnet.teleport.network
* https://evm-rpc1.testnet.teleport.network
* https://evm-rpc2.testnet.teleport.network

**Tendermint RPC Endpoints:**

* https://rpc.testnet.teleport.network
* https://rpc0.testnet.teleport.network
* https://rpc1.testnet.teleport.network
* https://rpc2.testnet.teleport.network

**gPRC Endpoints:**

* grpc://grpc0.testnet.teleport.network:443
* grpc://grpc1.testnet.teleport.network:443
* grpc://grpc2.testnet.teleport.network:443

### Seeds & Peers

You can find seeds & peers on the [seeds.txt](./seeds.txt) and [peers.txt](./peers.txt) files, respectively. If you want to share your seed or peer, please fork this repo and and add it to the bottom of the corresponding `.txt` file.

