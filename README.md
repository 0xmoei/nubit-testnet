![GO5Sm3kWkAA-rsv](https://github.com/0xmoei/nubit-testnet/assets/90371338/24288f69-5e2e-4509-a589-c5b6e2bdd622)

## Official Links
 * [Moei Twitter](https://twitter.com/0xMoei)
 * [Nubit Discord](https://discord.gg/nubit)
   
<h1 align="center"> Nubit Incentivized Alpha Testnet </h1>

A native Bitcoin DA layer has announced that its Alpha testnet incentive program is now live. The Alpha testnet event is divided into three phases: community assembly, light node missions, and testnet adventures, with incentives offered at each stage.

> Phase 1 is active
> Join [Testnet Dashboard](https://alpha.nubit.org)

<h1 align="center"> Nubit Light DA Node </h1>

> Light Node is a phase 2 task but better you run it now

## System Requirements
| Ram | cpu     | disk                      |
| :-------- | :------- | :-------------------------------- |
| `500MB`      | `Signle Core` | `+30GB SSD` |

## Dependecies
```console
sudo apt-get update && sudo apt-get upgrade -y 
sudo apt-get install curl screen git-all build-essential glibc-source pkg-config libssl-dev clang git-lfs -y
```
## Install & Run
```console
# Open a screen
screen -S nubit

# Install and Run
curl -sL1 https://nubit.sh | bash
```
> You can minimze the screen with Ctrl+A+D

## Save Mnemonic (12 Words)
```console
sudo cat $HOME/nubit-node/mnemonic.txt
```
## Optional: Logs
```console
# Check logs
screen -r nubit

# minimze again
CTRL + A + D
```

## Optional: Restart Node (if needed)
```console
cd $HOME && cd nubit-node
./start.sh
```

## Optional: Delete node
```console
 rm -rf $HOME/nubit-node $HOME/.nubit-light-nubit-alphatestnet-1
```
