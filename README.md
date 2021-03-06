# MyBlackAppleEFI
我的黑苹果Clover EFI配置

# 我为什么要弄一台黑苹果
家境贫寒，价格劝退。（说到贫寒我就想起了宋濂的《送东阳马生序》吾家贫，无从致mac以用。🌹🐔）

# 主板设置
更新了最新bios(version:2012)的主板需要前往bios中更改
```
Advanced —> Onboard Devices Configuration-Serial Port Configuration Serial Port —> Off
Advanced —> USB Configuration-XHCI Hand-off —> Enabled
Secure Boot -> OS Type -> Other OS
Advanced —> PCH configuration-IOAPIC 24-119 Entries —> disabled
CFG-LOCK -> disabled
Advanced -> Advanced PCH Configuration -> system time and alarm source -> Legacy RTC
```

# 配置如下

| 项目        | 配置   |
| --------   | :-----  |
| CPU        |英特尔（Intel）i5-9600K | 
|内存         |美商海盗船（CORSAIR） 复仇者8G DDR4 2666 X2|
| 主板        |华硕（ASUS）TUF B360M-PLUS GAMING S   | 
| 显卡        |蓝宝石（SAPPHIRE）RX470 4G DDR5超白金（闲鱼入的锻炼卡）    | 
| 硬盘        |惠普（HP） EX900系列 250G M.2 NVMe SSD    | 
|无线网卡      |BCM94360CS2 (免驱WIFI和蓝牙)|

# 桌面展示
<img src="screenshots/41589552231_.pic_hd.jpg" width="200" height="200" />

# 问题解决

- [x] 显卡免驱完美
- [x] 有线以太网卡完美
- [x] 声卡（有声音，可使用siri）
- [x] 使用独显后无法使用预览查看JPG图片
- [x] USB3.1完美
- [x] 完美睡眠唤醒
- [x] 可登陆icloud，app store正常
- [x] 可以更新到最新macOS版本

# 截图展示

## 10.15.4
![10.15.4](screenshots/WX20200515-221048.png)
## 10.15.1
升级到10.15.1需要将`WhateverGreen`更新到`V1.3.4`，否则会黑屏。[详情链接](https://osx.cx/whatevergreen-kext-amd.html)
![10.15.1](screenshots/WX20191119-222840.png)
## 10.15
![10.15](screenshots/WX20191119-220110.png)
## 10.14.6
![10.14.6](screenshots/WX20190724-220055.png)
## 10.14.5
![10.14.5](screenshots/WX20190724-214915.png)

# 更新记录
## 2020.5.15

