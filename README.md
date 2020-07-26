# 树莓派更换软件源一键脚本
## 说明
此脚本可同时更换`apt`、`pip`、`docker`、`npm`源为国内源，适用于`RaspiOS Buster`（原`Raspbian`）。
其中`apt`、`pip`换成清华源，`docker`换成中国区官方源，`npm`换成淘宝源。有特殊需求的可以自行修改脚本。
## 使用
1. 先使用`wget https://raw.githubusercontent.com/hmsjy2017/rpi-mirror-change/master/change-mirror.sh`下载脚本，如果提示`403`，说明域名被墙，请执行`wget https://gitee.com/iamsjy/rpi-mirror-change/raw/master/change-mirror.sh`。
2. 然后输入`sudo chmod +x change-mirror.sh`赋予脚本执行权限，否则会因为权限不足而无法运行。
3. 输入`sudo sh change-mirror.sh`运行脚本。

合起来就是`wget https://gitee.com/iamsjy/rpi-mirror-change/raw/master/change-mirror.sh && sudo chmod +x change-mirror.sh && sudo sh change-mirror.sh`
