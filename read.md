geth --rpc --rpcport 8545 --rpccorsdomain * --datadir ./testChain/ --port 30304 --rpcapi db,eth,net,web3 --fast --cache=2048 --networkid 4449 --bootnodes enode://2e8045ea3d42b1c0dbd9d5bf1ed6b8c908584429236add6163ee7ce9899569ee31a9f45a8ca77cd3bf77c365ad7ed3b29f146df7fd1b7e2c20d86fc0ec23f245@192.168.51.202:30304 init ./testChain/genesis.json


geth --rpc --rpcport 8545 --rpccorsdomain * --datadir ./testChain/ --port 30304 --rpcapi db,eth,net,web3 --fast --cache=2048 --networkid 4449 --bootnodes enode://2e8045ea3d42b1c0dbd9d5bf1ed6b8c908584429236add6163ee7ce9899569ee31a9f45a8ca77cd3bf77c365ad7ed3b29f146df7fd1b7e2c20d86fc0ec23f245@192.168.51.202:30304 console
