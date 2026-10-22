# Armbian-on-Allwinner-A20-TVBOX 
## 用它创建属于开博尔全志A20系列机顶盒的 Armbian Linux.
###  开博尔全志A20系列 机顶盒常见型号有A1、Q7、K610i九代、C3九代、K10升级版等，多采用同一主板。项目基于开博尔K610i九代，采用的是全志A20 32位SoC，1GB内存，4GB nand，2 USB，1 SD卡，Realtek RTL8201CP 以太网，Realtek RTL8188ETV 无线网，运行安卓4.2.2系统。这个项目的目的是创建一个能在K610i九代上运行的 Armbian Linux。为此我写了一些补丁脚本以及设备树，将它们运用在 Armbian Build中编译属于K610i九代的Linux 主线内核。
##  Build from source like
####  ./compile.sh BOARD=k610i-gen9 RELEASE=trixie BUILD_DESKTOP=no BUILD_MINIMAL=yes KERNEL_CONFIGURE=no
###  也可以使用我编译好的镜像直接从SD卡启动Armbian Linux.

