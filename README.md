# 树莓派更换软件源一键脚本
此脚本可同时更换`apt`、`pip`、`docker`、`npm`源为国内源，适用于`RaspiOS Buster`（原`Raspbian`）。

## 使用
1. 输入`sudo -i`切换为`root`用户，否则后面会因为权限不足而无法运行。
2. 先使用`wget https://raw.githubusercontent.com/hmsjy2017/rpi-mirror-change/master/change-mirror.sh`下载脚本，如果提示`403`，说明域名被墙，请执行`wget https://gitee.com/iamsjy/rpi-mirror-change/raw/master/change-mirror.sh`。
3. 然后`./change-mirror.sh`运行脚本。
