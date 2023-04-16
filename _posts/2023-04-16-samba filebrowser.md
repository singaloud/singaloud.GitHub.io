---
layout: post
title: samba 无法写入，filebrowser无法运行
author: Leopard
tags: [机顶盒，filebrowser，samba]
date: 2023-04-16 08:37 +0800

---
## （1）设置如下，sd卡写入了镜像，还有30g左右的剩余空间，格式化为ext4并挂载，在共享里添加挂载，能访问，但是没法写入，不知道什么问题。

### 解决方法：
SSH进去，设置目录权限 777
chmod -R 777 /mnt


## （2）openwrt下filebrowser设置主程序目录，并放置主程序文件，无法运行。

### 同样是：
SSH进去，设置目录权限 777
chmod -R 777 /mnt
