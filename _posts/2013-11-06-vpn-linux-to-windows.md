---
layout: blog
title: 连接 Windows Server VPN
tags: ArchLinux Bash IP Linux Ubuntu Windows 网络 远程桌面
---

Linux 连接 Windows Server VPN，以 archLinux 为例，适用于 Ubuntu。

1. 安装 pptp

    ```bash
    # kde in arch
    pacman -S extra/networkmanager-pptp
    ```

2. 新建 VPN 连接

    网关：服务器IP或域名
    登录：用户名
    密码：密码
    域：空
    认证方式：MSCHAP MSCHAPv2
    使用 MPPE 加密

