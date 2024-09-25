# T3rn_executor_node
Setting up T3RN Executor node on VPS

Welcome to t3rn, a Modular Interoperability Layer designed for fast, secure, and cost-efficient cross-chain swapping. t3rn is uniquely positioned to bridge the gaps in blockchain interoperability, offering superior swapping for users and yield for infra providers by becoming t3rn Executors.

Docs : [t3rn docs](https://docs.t3rn.io/intro) | X : [t3rn](https://x.com/t3rn_io)

----------------------------------------------------------------------------------------------------------------------------------------
### Getting Started with t3rn:
#### Participate as an Executor:
Join the network as an Executor to process transactions and engage in the ecosystem by bidding on orders and executing transactions.

#### Explore t3rn's Bridge UI:
Explore cross-chain swaps with our intuitive Bridge UI. Now live on testnets, it enables fast, secure, and cost-efficient cross-chain transactions.

Task : https://app.galxe.com/quest/t3rn/GC2NYtzDN6
[Answers : C, A, D, C]

Faucet : https://faucet.brn.t3rn.io/

Bridge : https://bridge.t1rn.io 

----------------------------------------------------------------------------------------------------------------------------------------

# Join Crypto Console Community

Join TG : [Crypto Console Telegram](https://t.me/cryptoconsol) | Follow X : [Crypto Console Twitter](https://www.x.com/cryptoconsol) | Subscribe : [Crypto Console Youtube](https://www.youtube.com/@cryptoconsole)

Crypto VPS : [https://vpsdime.com](https://vpsdime.com/a/4418/linux-vps)

----------------------------------------------------------------------------------------------------------------------------------------

### Update and upgrade system packages
```
sudo apt update
sudo apt upgrade
```
### Install fonts
```
sudo apt-get install figlet
figlet -f /usr/share/figlet/starwars.flf
```
### Download t3rn binaries
```
curl -L -o executor-linux-v0.21.4.tar.gz https://github.com/t3rn/executor-release/releases/download/v0.21.4/executor-linux-v0.21.4.tar.gz
```
### Extract 
```
tar -xzvf executor-linux-v0.21.4.tar.gz
```
```
cd executor/executor/bin
```

### Open screen 
```
screen -S t3rn
```
### Set your preferred Node Environment.
```
export NODE_ENV=testnet
```
### Set your log settings
```
export LOG_LEVEL=debug
export LOG_PRETTY=false
```
### PRIVATE KEYS
Set the PRIVATE_KEY_LOCAL variable of your Executor, Replace with your privatekey
```
export PRIVATE_KEY_LOCAL=<replace your privatekey>
```
### Set Networks
```
export ENABLED_NETWORKS='arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn'
```
### Start Node
```
./executor
```

Take a screenshot of running node and post it on discord to get a role.

Discord : https://discord.gg/tW9Zqacw

Join Crypto Console : [Community](https://t.me/cryptoconsol)
