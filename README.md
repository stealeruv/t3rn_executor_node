# t3rn_executor_node
Setting up T3RN Executor node on VPS


Task : https://app.galxe.com/quest/t3rn/GC2NYtzDN6

### Update and upgrade system packages
```
sudo apt update
sudo apt -y upgrade
```
### Install fonts
```
sudo wget -O /usr/share/figlet/starwars.flf https://raw.githubusercontent.com/xero/figlet-fonts/master/starwars.flf
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
### Start Node
```
./executor
```
export ENABLED_NETWORKS='arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn'
Take a screenshot and post it on discord to get a role.
