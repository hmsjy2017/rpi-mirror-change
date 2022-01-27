# 树莓派更换软件源一键脚本
## 说明
此脚本可同时更换`apt`、`pip`、`docker`、`npm`源为国内源，适用于`RaspiOS Buster`（原`Raspbian`）。
其中`apt`、`pip`换成清华源，`docker`换成中国区官方源，`npm`换成淘宝源。有特殊需求的可以自行修改脚本。
## 使用
```
curl -fSsL https://cdn.jsdelivr.net/gh/hmsjy2017/rpi-mirror-change@master/change-mirror.sh | sudo bash
```
