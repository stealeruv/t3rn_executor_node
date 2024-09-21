# t3rn_executor_node
Setting up T3RN Executor node on VPS


Task : https://app.galxe.com/quest/t3rn/GC2NYtzDN6

Faucet : https://faucet.brn.t3rn.io/

Bridge : https://bridge.t1rn.io 

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
curl -L -o executor-linux-v0.21.0.tar.gz https://github.com/t3rn/executor-release/releases/download/v0.21.0/executor-linux-v0.21.0.tar.gz
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
