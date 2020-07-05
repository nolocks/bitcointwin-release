### BITCOINTWIN
![image](https://pbs.twimg.com/profile_images/1179290642939146240/TNXUAheq_400x400.png)


##### Source
###### GITHUB - https://github.com/nolocks/bitcointwin  


##### Release
###### GITHUB - https://github.com/nolocks/bitcointwin-release  


##### Info
###### EXPLORER1 - http://block.bitcointwin.org  
###### EXPLORER2 - http://chain.bitcointwin.org  

##### API
###### EXPLORER1 - http://block.bitcointwin.org/api  
###### EXPLORER2 - http://chain.bitcointwin.org/api  

##### Transactions
###### `GET /tx/:txid`
###### `GET /tx/:txid/status`
###### `GET /tx/:txid/hex`
###### `GET /tx/:txid/raw`
###### `GET /tx/:txid/merkleblock-proof`
###### `GET /tx/:txid/merkle-proof`
###### `GET /tx/:txid/outspend/:vout`
###### `GET /tx/:txid/outspends`
###### `POST /tx`

##### Addresses
###### `GET /address/:address`
###### `GET /scripthash/:hash`
###### `GET /address/:address/txs`
###### `GET /scripthash/:hash/txs`
###### `GET /address/:address/txs/chain[/:last_seen_txid]`
###### `GET /scripthash/:hash/txs/chain[/:last_seen_txid]`
###### `GET /address/:address/txs/mempool`
###### `GET /scripthash/:hash/txs/mempool`
###### `GET /address/:address/utxo`
###### `GET /scripthash/:hash/utxo`
###### `GET /address-prefix/:prefix`

##### Blocks
###### `GET /block/:hash`
###### `GET /block/:hash/status`
###### `GET /block/:hash/txs[/:start_index]`
###### `GET /block/:hash/txids`
###### `GET /block/:hash/txid/:index`
###### `GET /block/:hash/raw`
###### `GET /block-height/:height`
###### `GET /blocks[/:start_height]`
###### `GET /blocks/tip/height`
###### `GET /blocks/tip/hash`

##### Mempool
###### `GET /mempool`
###### `GET /mempool/txids`
###### `GET /mempool/recent`

##### Pool  
###### POOL1  
###### - MINING - `[minerd -a sha256d -o stratum+tcp://shortbread.pool.bitcointwin.org:3001 -u [address]]`  

###### POOL2
###### - MINING - `[minerd -a sha256d -o stratum+tcp://compote.pool.bitcointwin.org:3001 -u [address]]`  

###### POOL3
###### - MINING - `[minerd -a sha256d -o stratum+tcp://caramel.pool.bitcointwin.org:3001 -u [address]]`  

###### POOL4
###### - MINING - `[minerd -a sha256d -o stratum+tcp://screw.pool.bitcointwin.org:3001 -u [address]]`  


##### Social
###### TWITTER - https://twitter.com/bitcointwin  
###### DISCORD - https://discord.gg/cGMZDH  


##### Nodes
###### NODE1 - 134.0.115.57:8333  
###### NODE2 - 134.0.119.149:8333  


##### Prerequisites
- `sudo apt-get update`  
- `sudo apt-get install software-properties-common libssl-dev libevent-dev libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev -y`  
- `sudo add-apt-repository ppa:bitcoin/bitcoin -y`  
- `sudo apt-get update`  
- `sudo apt-get install libdb4.8-dev libdb4.8++-dev -y`  


##### Run
- `bitcoind --daemon -addnode=134.0.119.149:8333 -addnode=134.0.115.57:8333 -listen=1`  
