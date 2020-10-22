# Opencore-I5-4590-ASUS-H81M-K

# 请自行生成PlatformInfo填入！！！！！！！可选机型iMac15，1

## 配置

| 设备 |          型号          |
| :--: | :--------------------: |
| CPU  |        I5-4590         |
| 主板 |      ASUS H81M-K       |
| 显卡 | Intel HD Graphics 4600 |
| 网卡 |      Realtek 8111      |

## 功能

| 功能     | 完成度                                    |
| -------- | ----------------------------------------- |
| CPU 变频 | 正常                                      |
| 核显     | 硬件加速正常                              |
| 声卡     | 直接驱动，且使用 id 为 3，完美适配本主板      |
| 网卡     | 正常                                      |
| 睡眠     | 正常                                      |
| USB      | 已定制，正常                              |

## 已知问题

暂无，如存在请反馈😊。

## 主要驱动

|        驱动         |  版本  |
| :-----------------: | :----: |
|      Lilu.kext      | latest |
|   VirtualSMC.kext   | latest |
| WhateverGreen.kext  | latest |
| RealtekRTL8111.kext | latest |
|    AppleALC.kext    | latest |


## BIOS 设置

|      关闭       |              开启               |
| :-------------: | :-----------------------------: |
|    Fast Boot    |          EHCI Hand-off          |
|   Secure Boot   |         Intel xHCI mode         |
| Serial/COM Port |        IGPU memory: 64MB        |
|      VT-d       |         SATA Mode: AHCI         |
|       CSM       |       Excuse Disable Bit        |
|    CFG Lock     |  OS type: Windows 10 UEFI mode  |
|  Parallel Port  | Intel Virtualization Technology |



## 引导及系统版本
已经测试支持Catalina全部，Big Sur DB10

## 参考
https://github.com/VanXNF/Hackintosh-I5-4590-ASUS-H81M-D-R2.0
