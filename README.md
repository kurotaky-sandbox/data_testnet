## KDC

## geth

```
nohup geth --networkid 4649 --nodiscover --maxpeers 0 --datadir ~/data_testnet --mine --minerthreads 1 --rpc --rpcaddr "0.0.0.0" --rpcport 8545 --rpccorsdomain "*" --rpcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3" --unlock 0,1 --password ~/data_testnet/passwd --verbosity 6 2>> ~/data_testnet/geth.log
```

## Remix
https://github.com/ethereum/browser-solidity

```
npm start
```
