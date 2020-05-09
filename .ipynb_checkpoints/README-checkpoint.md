# Blockchain Project

## Starting the Network

We first start the network by creating nodes in the geth. initialize the nodes and use those nodes to create a netwok in Puppeth. 

We need to install Geth & tools 1.9.7 and my crypto. the gethflags you need start mining and connecting with nodes are as follows:

## Initializing the nodes

for the first node you will use ./geth --datadir richnode1 --mine --minerthreads 1 --unlock "0x30E6199a431FCC5f0d92A53147128dB7fEf93078" --password "C:\Program Files\Git\password.txt" --allow-insecure-unlock

and for the second node you will use ./geth --datadir richnode2 --port 30304 --rpc --bootnodes "enode://2b88eea5e6ad215b76b4a8a6c3b95b33e965ac641307cb784f
e79b0726fe3afc8146475837b9f7c6332e9597de38051df56459f02fb7c364d4ba07955a1cf01a@127.0.0.1:30303" --ipcdisable --unlock "
0x95121389FE9f772B20542f0B824b902f6CBC35D9" --password "C:\Program Files\Git\password.txt" --allow-insecure-unlock

## Sending Transactions

we set the blocktime to three seconds, the chain ID was 37 account passwords can be found in the "publicaddresses.txt" file, though a seperate password file is needed to be used in the command line. 

To connect to MyCrypto, you use the same chain ID that was used to make the nodes. Use the default HTTP link to connect to your machine. From there connect to the node that has the RCP exposure to send bitcoins to the other node.