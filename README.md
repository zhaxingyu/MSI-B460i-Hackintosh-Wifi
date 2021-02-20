# MSI-B460i-Hackintosh（Intel iGPU&Native Wifi/BT）
## EFI 
OpenCore: 0.6.7

macOS version: 11.2

## 功能测试
- [✓] 睡眠/唤醒
- [✓] Windows引导
- [✓] 所有USB端口
- [✓] 核显硬件加速
- [✓] 板载蓝牙/WiFi
- [✓] 板载声卡输出
- [✓] 显示器输出
- [✓] HDMI/DP音频

## 硬件配置
| 规格     | 详细信息                                     |
| -------- | ---------------------------------------- |
| 主板型号 | 微星 MSI B460I GAMING EDGE WIFI |
| 处理器 | 英特尔 酷睿 i7-10700 处理器 |
| 内存 | 16GB 英睿达 DDR4 2933MHz C15 |
| 硬盘 | 海康威视 C2000PRO 1TB |
| 集成显卡 | 英特尔 超核芯显卡 UHD630 |
| 显示器 | AOC CU34G2X UWQHD 3440x1440 （34英寸） |
| 声卡 | 瑞昱 ALC1220/1200 |
| 无线网卡 | 英特尔 Wireless-AX200|

## 注意事项
  1.序列号需使用opencore configurator 选择iMac 20,1型号生成三码，分别填入config.plist中的MLB(Board Serial Number)，SystemSerialNumber，SystemUUID中
  
  2.BIOS需要进行一些设置，否则卡logo 设置指南:https://b23.tv/Pc85I5 
  
  注:  
  
       --cfg-lock必须关闭
       
       --intel vt-d技术不影响黑苹果使用，有使用虚拟机需求的不用关闭
       
       --fast boot不影响使用，可开启
       
       --Above 4G decoding必须开启
       
       --DVMT Pre-Allocated(iGPU Memory): 64MB
       
       --Secure Boot必须关闭
