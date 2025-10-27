# patches-for-dahdi-linux
If it fails due to issues with dahdi-linux when you building OpenWrt 24.10.4 image,  you can use there patches.
There 4 patches was fixed dahdi-linux "MAX" problem.
Just put that total 4 patches into "~/openwrt/feeds/telephony/libs/dahdi-linux/patches" 
Then “make world” or “make package/feeds/telephony/dahdi-linux/compile V=s”
