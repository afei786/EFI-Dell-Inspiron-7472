# Dell Inspiron 7472 DW1560 OC文件

## 安装配置

* OpenCore版本：0.9.1
* MacOS版本：12.5 （后升级到13.5.1）

## BIOS设置

* 关闭『安全引导』

* 开启AHCI

* 关闭『Enable Legacy Option ROMs』

## 特别注意

* Msr请自行解锁，如果不想解锁，可在配置文件里面勾选“AppleXcpmCfgLock”，否则引导过程中会卡住

* 关于机型的选择，个人推荐“MacBookAir8,2”，这个选择从CPU的频率策略上来说，算是非常平衡的，当然选择其他机型也是能正常运转的，可根据自己的喜好进行合理选择

## 机器配置

* BIOS版本：1.11.0（建议更新BIOS）

* CPU：i5-8250U

* 声卡：ALC256，声卡ID使用69（十进制），驱动文件名称为ALC256.kext，最新版可在此下载[https://github.com/ic005k/ALC256]

* 内存：8G

* 核显：UHD 620

* 独显：无

* 硬盘：256G SSD

* 无线网卡：Dell DW1560（拆机更换的，原机无线网卡为DW1820，黑苹果无法驱动WiFi和蓝牙）

## 参考

* 本项目参考了ic005k[https://github.com/ic005k/DELL7472] 黑苹果项目，感谢ic005k大佬的付出
* 唯一改动是拆机更换无线网卡Dell DW1560，可以正常使用WiFi，蓝牙，隔空投送，接力。其余均未改动
* 无线网卡驱动参考了b站博主853491的文章中的DW1560驱动方法[https://www.bilibili.com/read/cv15626222/]
