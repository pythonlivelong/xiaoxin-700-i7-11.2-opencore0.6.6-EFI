# xiaoxin-700-i7-11.2-opencore0.6.6-EFI
此项目是基于macOS bigsur 11.2 的小新700-i7的引导文件。
其中debug版会显示启动代码，用户可根据代码调试自己的机型。
将此efi文件夹放在efi分区中，利用此引导分区启动小新700结合macOS bigsur 11.2镜像，即可安装macOS bigsur 11.2系统
经测试，除独立显卡（无解）无法正常使用、hdmi只有在关机后插入再开机可以使用（只能显示屏幕镜像，目前无解），其他功能完全正常，在更换免驱网卡后（未更换只能插线使用随行）可以无线使用随行利用iPad拓展显示屏。
