# bitcoind configuration for mainnet and testnet
# /home/bitcoin/.bitcoin/bitcoin.conf


 # Options for mainnet
  [main]

 # Bitcoind options
 server=1
 

 # Connection settings
 rpcuser=bitcoinmainnetusername
 rpcpassword=bitcoinmainnetpassword
 onlynet=ipv4
 zmqpubrawblock=tcp://127.0.0.1:29000
 zmqpubrawtx=tcp://127.0.0.1:29001

 # Raspberry Pi optimizations
 dbcache=100
 maxorphantx=10
 maxmempool=50
 maxconnections=40
 maxuploadtarget=5000
 log-level=debug
 txindex=1

 # Location of your external drive with Bitcoin's blockchain data 
 datadir=/media/hdd/bitcoin



 # Options for testnet
 [test]

 #remove the '#' below to enable Bitcoin testnet
 testnet=1

 #Bitcoind options
 server=1
 

 #Connection settings
 rpcuser=bitcointestnetusername
 rpcpassword=bitcointestnetpassword
 onlynet=ipv4
 zmqpubrawblock=tcp://127.0.0.1:28332
 zmqpubrawtx=tcp://127.0.0.1:28333

 #Raspberry Pi optimizations
 dbcache=100
 maxorphantx=10
 maxmempool=50
 maxconnections=40
 maxuploadtarget=5000
 log-level=debug
 txindex=1
 # Location of your external drive with Bitcoin's blockchain data 
 datadir=/media/hdd/bitcoin
