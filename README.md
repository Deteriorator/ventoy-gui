# ddk-ventoy
是U盘装系统神器 - Ventoy 的deepin桌面版
Ventoy的特点有:
完全开源免费，使用简单
快速，你拷贝有多快就有多快
直接从ISO文件启动，无需解开
无差异支持Legacy BIOS 和 UEFI模式
支持大于4GB的ISO镜像
不借助其他引导程序，保留ISO文件原始启动菜单
支持大部分常见操作系统
不只是启动，而是完整的安装过程
提出“Ventoy Compatible”概念
支持插件扩展
启动时U盘支持写保护
不影响U盘作为普通存储介质的使用
版本升级时U盘文件可安全保留
无需跟随特定操作系统版本升级而升级
Ventoy官方原版下载： http://www.ventoy.net

原理：
    调用  fdisk -l   获取磁盘信息，然后用正则搜索移动设备显示在选择列表框。   
使用方法：
   先下载Ventoy安装包，解压后把程序复制到此目录执行。
   
   更新记录：
2020.04.21 10:47
更新了下正则规则，欢迎失败的同学重新下载测试！ 
2020.04.21 14:33
调整界面,修改为中文，修复bug
2020.04.23 04:16
1.调整界面,自写验证模块；
2.修复因编码问题造成其他系统识别不到U盘的BUG;

PS: 东西虽然小，但做为练手还是比较合适的，通过源码可以了解到QT信号与槽的工作机制，还有其他小技巧，值得参考。


   