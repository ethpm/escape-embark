# escape-embark
Ethereum Package Registry (Embark)

### Install

```shell
$ git clone --recursive https://github.com/ethpm/escape-embark.git
```

### Update registry contracts

Work-in-progress registry contracts for EthPM V2 are located [here](https://github.com/ethpm/escape-truffle/tree/master/contracts) and available to this repo via a submodule housed in the`registry` folder. To update the contents
of `app/contracts` with latest `solidity` changes run:

```shell
$ npm run update:registry  # Then commit, push.
```


