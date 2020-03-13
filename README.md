# BITCOINTWIN

#### INFO
DISCORD - https://discord.gg/cGMZDH  
GITHUB - https://github.com/nolocks/bitcointwin  
EXPLORER1 - http://block.bitcointwin.org  
EXPLORER2 - http://chain.bitcointwin.org  
P2POOL1 - http://caramel.p2pool.bitcointwin.org  
P2POOL2 - http://compote.p2pool.bitcointwin.org  
P2POOL3 - http://shortbread.p2pool.bitcointwin.org  

#### NODES
NODE1 - 134.0.115.57:8333  
NODE2 - 134.0.119.149:8333  

#### BEFORE
`sudo apt-get update`  
`sudo apt-get install software-properties-common libssl-dev libevent-dev libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev -y`  
`sudo add-apt-repository ppa:bitcoin/bitcoin -y`  
`sudo apt-get update`  
`sudo apt-get install libdb4.8-dev libdb4.8++-dev -y`  

#### RUN
`bitcoind --daemon -addnode=134.0.119.149:8333 -addnode=134.0.115.57:8333 -listen=1`  
