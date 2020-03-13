### BITCOINTWIN

##### Source
GITHUB - https://github.com/nolocks/bitcointwin  

##### Release
GITHUB - https://github.com/nolocks/bitcointwin-release  

##### Info
EXPLORER1 - http://block.bitcointwin.org  
EXPLORER2 - http://chain.bitcointwin.org  
P2POOL1 - http://caramel.p2pool.bitcointwin.org `[minerd -a sha256d -o stratum+tcp://80.78.240.191:9332 -u [address] -p awd -t 1]`  
P2POOL2 - http://compote.p2pool.bitcointwin.org `[minerd -a sha256d -o stratum+tcp://151.248.114.191:9332 -u [address] -p awd -t 1]`  
P2POOL3 - http://shortbread.p2pool.bitcointwin.org `[minerd -a sha256d -o stratum+tcp://80.78.248.25:9332 -u [address] -p awd -t 1]`  

##### Social
TWITTER - https://twitter.com/bitcointwin  
DISCORD - https://discord.gg/cGMZDH  

##### Nodes
NODE1 - 134.0.115.57:8333  
NODE2 - 134.0.119.149:8333  

##### Prerequisites
- `sudo apt-get update`  
- `sudo apt-get install software-properties-common libssl-dev libevent-dev libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev -y`  
- `sudo add-apt-repository ppa:bitcoin/bitcoin -y`  
- `sudo apt-get update`  
- `sudo apt-get install libdb4.8-dev libdb4.8++-dev -y`  

##### Run
- `bitcoind --daemon -addnode=134.0.119.149:8333 -addnode=134.0.115.57:8333 -listen=1`  
