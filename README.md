# ethereum-docker
Docker image that will generate a single node ethereum network

# Getting started

## 1. Installing

### 1.1 Single Node Ethereum

#### Prerequisites

Docker Toolbox installed. Goto [Docker Toolbox](https://www.docker.com/products/docker-toolbox). 

After Docker Toolbox has been installed, create a ```default``` machine to run Docker against.

#### Running a node

Clone the repository

'''
git clone https://github.com/manojpramesh/eth-docker-panel.git
'''

Run the following to create a single node network:

```
$ docker-compose -f docker-compose-standalone.yml up -d
```

To access the JSON RPC client, use the following end point

```
http://$(docker-machine-ip-address):8545
```

### 1.1 Multi node Ethereum with network monitoring

WIP


## 2. Test Accounts 

As part of the bootstrapping process we included 4 accounts pre-filled with 1000 ethers by default.

Password : Innov@te@ey

1. 0x80a093906307ca03df8383eff05fb8957e852e43
2. 0x2e884d0e0c9ba6c3b7c1a495cdcae319519a8884
3. 0x76ad7c62dbfee3225048ded12d9472a695b20bd3
5. 0xb7d1973a24b7185f8c895a3f9316868c5aeb4f8a