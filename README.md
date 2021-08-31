# MSI GS65 9SE OPENCORE and CLOVER hackintosh 微星GS65黑苹果oc efi
## MSI GS65-9se hackintosh EFI is different from the motherboard of the 8th generation, only the 9th generation is available.

+ CPU: i7 9750h
+ GPU: 2060 (disable)
+ Memory: 16g
+ Disk: 1t SN550
+ Network: dw1820a (everything working)

## Issues to be solved
+ Touch board touching by mistake (voodooi2c with high sensitivity can't solve)
+ can't drive gtx2060 
+ Only external docking stations can use HDMI and DP
+ ~~didn't upgrade to oc.~~
+ ~~can't upgrade to big sur.No logo named install macos big sur~~(oc update successfully)

## Notice
+ change usbports.kext to usbinjectall.kext before install
+ opencore version support bigsur.clover don't support.

## 待解决问题：
+ 触控板打字误触 (暂时无解 使用VOODOOI2C，灵敏度较高)
+ 2060无法驱动，禁用
+ hdmi和dp接口无法直插，外接显示屏需要降低board-id版本，通过扩展坞走cpu。
+ ~~睡眠发热严重~~（定制usb解决）
+ ~~随航不可用~~（升级clover至最新版解决）
+ ~~暂未更新oc，看后期是否苹果会出11代u~~(已更新)
+ ~~更新bigsur 引导界面无法出现install macos big sur~~（oc版本安装成功） 

## 微星GS65 9SE 黑苹果clover EFI 和8代的主板有些区别，仅9代可用。
## usbports.kext为定制usb，建议先换位usbinjectall.kext,安装后再重新定制。
## 注意网卡为dw1820a，非该网卡需要进行修改
## 安装前记得重生生成三码
## 欢迎交流分享，帮助完善本机型 EFI
## Welcome to make contribution to GS65-9SE EFI
## 已换机，efi后期不再更新
