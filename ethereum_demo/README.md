
## Overview
 We'll build a simple Ethereum smart contract and lightwallet example. Any problems running the code? See the [issues
](https://github.com/eshon/conference/issues) section.


### Updates

Current code uses *Truffle v2.0.4*


### Install

Install [testrpc] (or use geth)

```
$ npm install -g ethereumjs-testrpc
```

Install [truffle](https://github.com/consensys/truffle):

```
$ npm install -g truffle@2.0.4
```

If you don't have solc you can get it [here](https://github.com/ethereum/go-ethereum/wiki/Contract-Tutorial#using-an-online-compiler)

### Run

Run testrpc in one console window:

```
$ testrpc
```
In another console window run truffle from project root directory:

```
$ truffle compile
$ truffle migrate
$ truffle test
$ truffle serve // server at localhost:8080
```


## Credits

Credits for this code go to [eshon](https://github.com/eshon). Its just a wrapper around it

