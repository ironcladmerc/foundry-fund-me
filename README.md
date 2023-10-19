## What this project is

This is a crowdsourcing smart contract. It allows funding the contract, keeps track of funders, and allows the owner to withdraw at any time. It could be used as a backend for web3 crowdsourcing websites, allowing for more reliable funding instead of having to trust a 3rd party company.

## Usage

### Build

```shell
$ make build
```

### Test

```shell
$ make test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/DeployFundMe.s.sol:DeployFundMe --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
