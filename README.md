# bitcoin.conf

# bitcoind MAINNET configuration
 2 # /home/bitcoin/.bitcoin/bitcoin.conf
 3
 4
 5 # Options for mainnet
 6  [main]
 7
 8 # Bitcoind options
 9 server=1
10 daemon=1
11
12 # Connection settings
13 rpcuser=bitcoinmainnetusername
14 rpcpassword=bitcoinmainnetpassword
15 onlynet=ipv4
16 zmqpubrawblock=tcp://127.0.0.1:29000
17 zmqpubrawtx=tcp://127.0.0.1:29001
18
19 # Raspberry Pi optimizations
20 dbcache=100
21 maxorphantx=10
22 maxmempool=50
23 maxconnections=40
24 maxuploadtarget=5000
25 log-level=debug
26 txindex=1
27
28 # Location of your external drive with Bitcoin's blockchain data 
29 datadir=/media/hdd/bitcoin
30
31
32
33 # Options for testnet
34 [test]
35
36 #remove the '#' below to enable Bitcoin testnet
37 testnet=1
38
39 #Bitcoind options
40 server=1
41 daemon=1
42
43 #Connection settings
44 rpcuser=bitcointestnetusername
45 rpcpassword=bitcointestnetpassword
46 onlynet=ipv4
47 zmqpubrawblock=tcp://127.0.0.1:28332
48 zmqpubrawtx=tcp://127.0.0.1:28333
49
50 #Raspberry Pi optimizations
51 dbcache=100
52 maxorphantx=10
53 maxmempool=50
54 maxconnections=40
55 maxuploadtarget=5000
56 log-level=debug
57 txindex=1
58 # Location of your external drive with Bitcoin's blockchain data 
59 datadir=/media/hdd/bitcoin
