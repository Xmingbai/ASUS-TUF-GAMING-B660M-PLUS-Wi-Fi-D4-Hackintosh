# ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh （B660重炮手）

# 本块主板测评视频链接：https://www.bilibili.com/video/BV12L411V7dg

# 也欢迎关注B站UP：小明和他的女朋友   

# 淘宝店铺：小明白工作室

===============================================================================
# Ver0.8.3  ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh  opencore0.8.3正式版 （B660重炮手）

1.更新至0.8.3正式版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x、MacOS 13 beta 5

2.更新Kexts至最新版本，支持新出售的重炮手声卡

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

4.引导默认支持PCIEx1 的博通无线和蓝牙，也支持板载 intel WiFi&BT 需使用 config-intelWIFI&BT.plist 改名为config.plist来使用

5.重新定制15个USB端口，保留前置USB（USB3+TYPE-C）

6.新增支持RX6650XT和RX6950XT，需在ACPI中勾选对应SSDT补丁才能启用。
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/RX6650XT%26RX6950XT.png)

不同主板请确认DSDT中显卡路径，参考视频教程：https://www.bilibili.com/video/BV1D541197yT

===============================================================================
# Ver0.8.2  ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh  opencore0.8.2正式版 （B660重炮手）

1.更新至0.8.2正式版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x、MacOS 13 beta 2

2.更新Kexts至最新版本，支持新出售的重炮手声卡；

3.默认config.plist 支持12代所有大小核心CPU型号，可同时开启大小核心；没有小核心的CPU型号，需关闭provideCurrentCpuInfo；

支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

4.引导默认支持PCIEx1 的博通WIFI和蓝牙，板载 intel WiFi 需去config 手动启用

5,重新定制15个USB端口，保留前置USB（USB3+TYPE-C）

6.新增支持RX6650XT和RX6950XT，需在ACPI中勾选对应SSDT补丁才能启用。

![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/RX6650XT%26RX6950XT.png)

不同主板请确认DSDT中显卡路径，参考视频教程：https://www.bilibili.com/video/BV1D541197yT

===============================================================================
# Ver0.8.0  ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh  opencore0.8.0正式版 （B660重炮手）
1.更新kexts至最新，更新至OC0.80正式版，支持Catalina、big sur、Monterey12.4版本

2.修复睡眠秒醒问题，关闭USB唤醒

3.支持12代所有大小核心CPU型号，可同时大小核心；没有小核心的CPU型号，需关闭provideCurrentCpuInfo

4.支持NAVI核心RX5500/5600/5700/6600/6800/6900系列显卡（vega核心系列显卡需去掉启动参数agdpmod=pikera）

5.重新定制15个USB端口，保留前置USB（USB3+TYPE-C）

# 6.新增支持RX6650XT和RX6950XT，需在ACPI中勾选对应SSDT补丁才能启用。
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/RX6650XT%26RX6950XT.png)
不同主板请确认DSDT中显卡路径，参考视频教程：https://www.bilibili.com/video/BV1D541197yT


===============================================================================


# 测评主机配置：

主板：ASUS TUF GAMING B660M PLUS WIFI D4

CPU：i5-12600K

显卡： 华硕 Dual -RX6600XT- O8G

内存：威刚D50  DDR4 3200  16x2

硬盘： SN750 500G（macOS 盘）+PM9A1 500G (Windows 11)

无线网卡：BCM94360CD 

===============================================================================

☆ kext驱动到最新正式版本

☆ 支持10.15.x及11.6.x及12.x

☆ 默认config支持5500/5600/5700/6600/6800/6900系列显卡


#  功能完善程度

☆ CPU 大小核心识别正常（C4D 渲染可以满载），没有小核心的CPU型号，需关闭provideCurrentCpuInfo

☆ USB3.0和2.0识别

☆ 2.5G有线网卡识别正常

☆ 声卡驱动正常（alcid=66）

☆ 本机显卡RX6600XT 识别正常，支持硬解

☆ 另加BCM94360CD WIFI与蓝牙正常，隔空投送正常

☆ 睡眠与唤醒正常，支持开机键唤醒

# 若有其他问题请加Q群：608352460，备注小明或者B站


# 淘宝店铺名：小明白工作室  店铺短网址：https://cn.hk.uy/PHe

# 主板bios设置

☆ 初始化 

☆ 关闭 serial port

☆ 关闭fast boot

☆ 开启 XMP

如果安装windows时没动过bios，默认状态下即可安装macOS


![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/1.png)

![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/2.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/DIMM.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/NVME.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/USB.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/RX6600XT.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/BT.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/BCM%20WIFI.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/audio.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/air%20drop.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/R23.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/Geekbench.png)
![](https://github.com/Xmingbai/ASUS-TUF-GAMING-B560M-PLUS-Wi-Fi-D4-Hackintosh/blob/main/C4d.png)


