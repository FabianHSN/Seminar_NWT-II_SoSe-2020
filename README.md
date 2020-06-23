```
 __   __  _______  _______  __   __  ___      _______  _______  
|  |_|  ||       ||       ||  | |  ||   |    |   _   ||  _    | 
|       ||    ___||  _____||  |_|  ||   |    |  |_|  || |_|   |
|       ||   |___ | |_____ |       ||   |    |       ||       |
|       ||    ___||_____  ||       ||   |___ |       ||  _   |
| ||_|| ||   |___  _____| ||   _   ||       ||   _   || |_|   |
|_|   |_||_______||_______||__| |__||_______||__| |__||_______|
```

**...our seminar/lecture repository of the networking group MeshLab @HS-Nodhausen**

### MeshLab - Networking Seminar & Material

This repository provides sofware tools and documentation used in the Networking courses at HSN (Nordhausen - University of Applied Sciences).
To create, configure, run and troubleshoot different network experiments a virtual machine (VM) based on OpenWrt Linux is used. 

### How to get startet with OpenWrt ?

As a initial starting point, the provided OpenWrt VM is based on VirtualBox and will be extended to other VM formats in the future. The Openwrt Linux is based on OpenWrt trunk x86_64 target.

## Useage of the precompiled OpenWrt VirtualBox Appliance

1. Prerequisite: install a VirtualBox environment suited for you local machine (https://www.virtualbox.org/)
2. Clone the content of this repossitory (via https download or git clone or by using your favorite git client)
3. Open VirtualBox and import the provided VM from: ./source/OpenWrt_MeshLab.ova
4. If necessary adapt the network adapter settings to your needs (default: bridged mode on adapter 1)
5. Start the OpenWrt_MeshLab VM and your are ready to play!

## Compile OpenWrt from scratch

1. Prerequisite: Get an OpenWrt build environment on your local machine (https://openwrt.org/docs/guide-developer/build-system/install-buildsystem)
2. Chekout current OpenWrt trunk to your local machine
2. Copy the OpenWrt config from ./source/.config into your OpenWrt env
3. Start cross compiling your OpenWrt: 'make'
