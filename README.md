[![Build Status](https://travis-ci.com/hanwckf/rt-n56u.svg?branch=master)](https://travis-ci.com/hanwckf/rt-n56u)
![GitHub All Releases](https://img.shields.io/github/downloads/hanwckf/rt-n56u/total)
[![release](https://img.shields.io/github/release/hanwckf/rt-n56u.svg)](https://github.com/hanwckf/rt-n56u/releases)

# README #

Welcome to the rt-n56u project

This project aims to improve the rt-n56u and other supported devices on the software part, allowing power user to take full control over their hardware.
This project was created in hope to be useful, but comes without warranty or support. Installing it will probably void your warranty. 
Contributors of this project are not responsible for what happens next.

### How do I get set up? ###

* [Get the tools to build the system](https://bitbucket.org/padavan/rt-n56u/wiki/EN/HowToMakeFirmware) or [Download pre-built system image](https://bitbucket.org/padavan/rt-n56u/downloads)
* Feed the device with the system image file (Follow instructions of updating your current system)
* Perform factory reset
* Open web browser on http://my.router to configure the services

### Contribution guidelines ###

* To be completed

***

### 特别说明 ###
* 汉化字典来自：https://github.com/gorden5566/padavan
* 更新日志：https://www.jianshu.com/p/d76a63a12eae

***

### 固件特点 ###
- 使用[gorden5566](https://github.com/gorden5566/padavan)的汉化字典
- aria2前端更换为[AriaNg](https://github.com/mayswind/AriaNg)
- [curl](https://github.com/curl/curl)可选编译可执行程序 ```CONFIG_FIRMWARE_INCLUDE_CURL```
- 可选关闭webui里不常用的vpn页面 ```CONFIG_FIRMWARE_WEBUI_HIDE_VPN```
- 使用了[PROMETHEUS](http://pm.freize.net/index.html)提供的部分补丁
- 使用了[Linaro1985/padavan-ng](https://gitlab.com/padavan-ng/padavan-ng)的部分软件包
- 可选以下插件：
>- [scutclient](https://github.com/hanwckf/scutclient) ```CONFIG_FIRMWARE_INCLUDE_SCUTCLIENT```
>- [gdut-drcom](https://github.com/chenhaowen01/gdut-drcom) ```CONFIG_FIRMWARE_INCLUDE_GDUT_DRCOM```
>- [dogcom](https://github.com/hanwckf/dogcom) ```CONFIG_FIRMWARE_INCLUDE_DOGCOM```
>- [minieap](https://github.com/hanwckf/minieap) ```CONFIG_FIRMWARE_INCLUDE_MINIEAP```
>- [njit-client](https://github.com/hanwckf/njit8021xclient) ```CONFIG_FIRMWARE_INCLUDE_NJIT_CLIENT```
>- [napt66](https://github.com/mzweilin/napt66) ```CONFIG_FIRMWARE_INCLUDE_NAPT66```
>- [ssr](https://github.com/shadowsocksr-backup/shadowsocksr-libev)/[ss](https://github.com/shadowsocks/shadowsocks-libev) ```CONFIG_FIRMWARE_INCLUDE_SHADOWSOCKS```
>- [ss-server](https://github.com/shadowsocks/shadowsocks-libev) ```CONFIG_FIRMWARE_INCLUDE_SSSERVER```
>- [softether-vpnserver](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_SERVER```
>- [softether-vpnclient](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CLIENT```
>- [softether-vpncmd](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CMD```
>- [dns-forwarder](https://github.com/aa65535/hev-dns-forwarder) ```CONFIG_FIRMWARE_INCLUDE_DNSFORWARDER```
>- [vlmcsd](https://github.com/hanwckf/vlmcsd) ```CONFIG_FIRMWARE_INCLUDE_VLMCSD```
>- [ttyd](https://github.com/tsl0922/ttyd) ```CONFIG_FIRMWARE_INCLUDE_TTYD```
>- [lrzsz](https://ohse.de/uwe/software/lrzsz.html) ```CONFIG_FIRMWARE_INCLUDE_LRZSZ```
>- [htop](https://hisham.hm/htop/releases/) ```CONFIG_FIRMWARE_INCLUDE_HTOP```
>- [nano](https://www.nano-editor.org/dist/) ```CONFIG_FIRMWARE_INCLUDE_NANO```
>- [iperf3](https://github.com/esnet/iperf) ```CONFIG_FIRMWARE_INCLUDE_IPERF3```
>- [dump1090](https://github.com/hanwckf/dump1090) ```CONFIG_FIRMWARE_INCLUDE_DUMP1090```
>- [rtl-sdr](https://github.com/osmocom/rtl-sdr) ```CONFIG_FIRMWARE_INCLUDE_RTL_SDR```
>- [samba3.6](https://gitlab.com/padavan-ng/padavan-ng/tree/master/trunk/user/samba36) ```CONFIG_FIRMWARE_INCLUDE_SMBD36```
>- [mtr](https://github.com/traviscross/mtr) ```CONFIG_FIRMWARE_INCLUDE_MTR```
>- [socat](http://www.dest-unreach.org/socat) ```CONFIG_FIRMWARE_INCLUDE_SOCAT```
>- [srelay](https://socks-relay.sourceforge.io) ```CONFIG_FIRMWARE_INCLUDE_SRELAY```
>- [mentohust](https://github.com/hanwckf/mentohust-1) ```CONFIG_FIRMWARE_INCLUDE_MENTOHUST```
>- [frpc](https://github.com/fatedier/frp) ```CONFIG_FIRMWARE_INCLUDE_FRPC```
>- [frps](https://github.com/fatedier/frp) ```CONFIG_FIRMWARE_INCLUDE_FRPS```
>- [tunsafe](https://github.com/TunSafe/TunSafe) ```CONFIG_FIRMWARE_INCLUDE_TUNSAFE```

- 已适配除官方适配外的以下机型
>- PSG1208
>- PSG1218
>- 5K-W20 (USB)
>- OYE-001 (USB)
>- NEWIFI-MINI (USB)
>- MI-MINI (USB)
>- MI-3 (USB)
>- MI-R3G (USB)
>- HC5661A
>- HC5761A (USB)
>- HC5861B
>- 360P2 (USB)
>- MI-NANO
>- MZ-R13
>- MZ-R13P
>- RT-AC1200GU (USB)
>- XY-C1 (USB)
>- WR1200JS (USB)
>- NEWIFI3 (USB)
>- B70 (USB)
>- A3004NS (USB)
>- K2P
>- K2P-USB (USB)
>- JCG-836PRO (USB)
>- JCG-AC860M (USB)
>- DIR-882 (USB)
>- DIR-878
>- MR2600 (USB)
>- WDR7300

***

### 编译说明 ###

* 安装依赖包
```shell
sudo apt update
sudo apt install unzip libtool-bin curl cmake gperf gawk flex bison nano xxd \
cpio git python-docutils gettext automake autopoint texinfo build-essential help2man \
pkg-config zlib1g-dev libgmp3-dev libmpc-dev libmpfr-dev libncurses5-dev libltdl-dev
```
* 克隆源码
```shell
git clone --depth=1 https://gitee.com/hanwckf/rt-n56u.git /opt/rt-n56u
#git clone --depth=1 https://github.com/hanwckf/rt-n56u.git /opt/rt-n56u
```
* 准备工具链
```shell
cd /opt/rt-n56u/toolchain-mipsel

# （推荐）下载预编译的工具链：
mkdir -p toolchain-3.4.x
wget https://github.com/hanwckf/padavan-toolchain/releases/download/v1.1/mipsel-linux-uclibc.tar.xz
tar -xvf mipsel-linux-uclibc.tar.xz -C toolchain-3.4.x

# 或者，也可以从源码编译工具链，这需要一些时间：
# Manjaro/ArchLinux 用户请使用gcc-8
./clean_toolchain
./build_toolchain

```
* (可选) 修改机型配置文件
```shell
nano /opt/rt-n56u/trunk/configs/templates/PSG1218.config
```
* 清理代码树并开始编译
```shell
cd /opt/rt-n56u/trunk
sudo ./clear_tree
sudo ./build_firmware_modify PSG1218
# 脚本第一个参数为路由型号，在trunk/configs/templates/中
# 编译好的固件在trunk/images里
```

***

### 请参阅 ###
- https://www.jianshu.com/p/cb51fb0fb2ac
- https://www.jianshu.com/p/6b8403cdea46
