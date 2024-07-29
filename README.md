# Actions-X-WRT / [x-openwrt-actions](https://github.com/QC3284/x-openwrt-actions)

Build X-wrt using GitHub Actions
![OpenWrt logo](https://raw.githubusercontent.com/x-wrt/com.x-wrt/master/x-wrt-logo/x-wrt-logo-Aldrich-raw.svg)
![github logo](https://raw.githubusercontent.com/QC3284/x-wrt-actions/main/oip-c.png)


## 说明 ##
- 采用[PTPT52's X-wrt](https://github.com/x-wrt/x-wrt)源码编译
- 处理器：ramips/mt7621（MediaTek MT7621）
- 固件管理界面：http://192.168.5.1/
- 管理界面账户/密码：admin/admin
- SSH登录账户/密码：root/admin
（需要进入界面-系统-管理权页面-开启SSH登录）
[X-WRT 开启ssh的方法](https://blog.x-wrt.com/docs/ssh-open/)
- 固件无线默认名称：X-WRT_XXXX，密码：88888888
- 每周六自动编译（偶尔会手动编译）
- 下载：https://github.com/QC3284/x-wrt-actions/releases
- 原版下载地址：
  https://downloads.x-wrt.com/rom/
- 注:
- 1.没有修改opkg软件源，需自己解决
- 2.本固件仍在测试中，稳定性较差
- 3.可能会出现各种奇奇怪怪的Bug
- 4.fork后，可自定义固件（没有说明，自行摸索）

## 状态 ##
编译状态：
[![](https://github.com/QC3284/x-wrt-actions/actions/workflows/Build-X-wrt.yml/badge.svg)](https://github.com/QC3284/x-wrt-actions/actions/workflows/Build-X-wrt.yml)

## 感谢 ##

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [PTPT52's X-wrt](https://github.com/x-wrt/x-wrt)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [kenzok8 openwrt-packages](https://github.com/kenzok8/openwrt-packages)
- [kenzol8 small](https://github.com/kenzok8/small)
