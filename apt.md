## 清华大学开源软件镜像站
http://mirrors.tuna.tsinghua.edu.cn/raspbian/raspbian/
```
# 编辑 `/etc/apt/sources.list` 文件，删除原文件所有内容，用以下内容取代：
deb http://mirrors.tuna.tsinghua.edu.cn/raspbian/raspbian/ buster main non-free contrib rpi
deb-src http://mirrors.tuna.tsinghua.edu.cn/raspbian/raspbian/ buster main non-free contrib rpi

# 编辑 `/etc/apt/sources.list.d/raspi.list` 文件，删除原文件所有内容，用以下内容取代：
deb http://mirrors.tuna.tsinghua.edu.cn/raspberrypi/ buster main ui
```

## 阿里巴巴镜像站
https://mirrors.aliyun.com/raspbian/raspbian/
```
编辑 /etc/apt/sources.list 文件，删除原文件所有内容，用以下内容取代：

deb https://mirrors.aliyun.com/raspbian/raspbian/ buster main non-free contrib
deb-src https://mirrors.aliyun.com/raspbian/raspbian/ buster main non-free contrib
```
## 中国科学技术大学开源软件镜像站
https://mirrors.ustc.edu.cn/raspbian/raspbian/
```
直接编辑 /etc/apt/sources.list 文件（需要使用 sudo）。删除原文件所有内容，用以下内容取代（以 Buster 示例）：

deb http://mirrors.ustc.edu.cn/raspbian/raspbian/ buster main contrib non-free rpi
#deb-src http://mirrors.ustc.edu.cn/raspbian/raspbian/ buster main contrib non-free rpi
编辑此文件后，请使用 sudo apt-get update 命令，更新软件索引。
```

## 北京外国语大学开源软件镜像站
https://mirrors.bfsu.edu.cn/raspbian/raspbian/
