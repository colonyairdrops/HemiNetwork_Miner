# HemiNetwork_Miner by @ColonyAirdrops
---
- Offical Docs - [Hemi_Miner_CLI](https://docs.hemi.xyz/how-to-tutorials/tutorials/setup-part-1)
- Watch Video to understand better

## 1. Binaries
- Visit [binaries](https://docs.hemi.xyz/how-to-tutorials/tutorials/setup-part-1)
- Download (heminetwork_v0.4.3_linux_amd64.tar.gz) file
- Use Termius and copy the file to your VPS

- Now Follow commands
```bash
sudo apt update && sudo apt upgrade -y
```
```bash
sudo apt install screen
```
```bash
screen -S hemi
```
```bash
tar xvf heminetwork_v0.4.3_linux_amd64.tar.gz
```
```bash
cd heminetwork_v0.4.3_linux_amd64
```

## 2. Verify Configuration Success
- To ensure you downloaded the correct binaries and are able to run them, execute the command below:
```bash
./popmd --help
```
- This will display the help menu for popmd, indicating that it's installed and operational.

## 4. Generate Your Public Key
```bash
./keygen -secp256k1 -json -net="testnet" > ~/popm-address.json
```
```bash
cat ~/popm-address.json
```
