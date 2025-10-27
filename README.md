# patches-for-dahdi-linux
If it fails due to issues with dahdi-linux when you building OpenWrt 24.10.4 image,  you can use there patches.

There 4 patches was fixed dahdi-linux "MAX" problem.

Just put that total 4 patches into "~/openwrt/feeds/telephony/libs/dahdi-linux/patches".

Then “make world” to building image，or “make package/feeds/telephony/dahdi-linux/compile V=s”

如果你在编译OpenWrt 24.10.4版本时，出现因dahdi-linux导致的编译失败，你可以该补丁文件。

这四个补丁是为了修复dahdi-Linux编译时的MAX宏名称问题。

直接将这四个补丁放置于"~/openwrt/feeds/telephony/libs/dahdi-linux/patches"内。

然后执行“make world”编译镜像，或者执行“make package/feeds/telephony/dahdi-linux/compile V=s”预编译dahdi-linux
