# Armbian-on-Allwinner-A20-TVBOX 
##  Use this Build Armbian for the Allwinner A20 series set-top boxes from Kaiboer.
###  The common models of Kaiboer Allwinner A20 series set-top boxes include A1, Q7, K610 Gen 9th, C3 Gen 9th, and K10 Upgrade Edition, which mostly use the same motherboard. The project is based on Kaiboer K610i Gen 9th, utilizing the Allwinner A20 32-bit SoC, 1GB of memory, 4GB of NAND, 2 USB ports, 1 SD card slot, Realtek RTL8201CP Ethernet, Realtek RTL8188ETV wireless network, and running Android 4.2.2 system.. 
###  The objective of this project is to develop an Armbian Linux distribution that can run on the  K610i Gen 9th TVbox. To achieve this, I have crafted several patch scripts and device tree modifications, which I have integrated into the Armbian Build process to compile the mainline Linux kernel tailored for the K610i Gen 9th TVbox.  
##  Build from source like
####  $./compile.sh BOARD=k610i-gen9 RELEASE=trixie BUILD_DESKTOP=no BUILD_MINIMAL=yes KERNEL_CONFIGURE=no
###  You can also use the image I compiled to directly boot Armbian from an SD card.

