# astrix-miner
astrix gpu miner release
V0.2.4
https://github.com/paragone/astrix-miner/releases/tag/V0.2.2

- dev fee 3% -> 2%
- Efficiency improvements (~10% - 20%)
- fix AMD GPU supports : especially 70 series ！！
- fix stratum protocol，now it‘s smooth

U can use pool url or xx.xx.xx.xx:34150 for solo

## windows 
```
.\astrix-miner.exe  -a WALLET
```
## linux
```
./astrix-miner  -a WALLET
```
## hiveos
url:
```
https://github.com/paragone/astrix-miner/releases/download/v0.2.4/astrix-miner-0.2.4.tar.gz
```
if u meet the GLIC error,run the command below:
```
echo "deb http://cz.archive.ubuntu.com/ubuntu jammy main" >> /etc/apt/sources.list && apt update && DEBIAN_FRONTEND=noninteractive apt install libc6 -y
```
![img](./config_en.png)
