[![Build OpenWrt](https://github.com/minax007/XIAOMI_MI-4A_Gigabit_OpenWrt/actions/workflows/build-snapshot.yml/badge.svg)](https://github.com/minax007/XIAOMI_MI-4A_Gigabit_OpenWrt/actions/workflows/build-snapshot.yml)
[![release](https://img.shields.io/github/v/release/minax007/XIAOMI_MI-4A_Gigabit_OpenWrt.svg)](https://github.com/minax007/XIAOMI_MI-4A_Gigabit_OpenWrt/releases)

# OpenWrt snapshot for Xiaomi Mi-4A Gigabit Edition (R4A) incl. LuCI

This GitHub action is to build fresh images of latest OpenWrt snapshot for the Mi-4A Gigabit Edition using imagebuilder.

![grafik](https://user-images.githubusercontent.com/67478561/227792070-021abc7e-b3e5-4f8b-966d-6e857bd579f8.png)

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**LuCI SQM (QoS)** | luci-app-sqm
**LuCI Adblock with DNS reporting** | luci-app-adblock & tcpdump-mini & curl
__________________________________________________________________
**Official OpenWrt snapshot of Mi-4A Gigabit Edition build without LuCI:**

https://firmware-selector.openwrt.org/?version=SNAPSHOT&target=ramips%2Fmt7621&id=xiaomi_mi-router-4a-gigabit
__________________________________________________________________
**Official OpenWrt snapshot download directory for MT76x8 routers, which includes the imagebuilder used in this action script:**

https://downloads.openwrt.org/snapshots/targets/ramips/mt7621/

__________________________________________________________________
This repository was  forked from https://github.com/amaumene/xiaomi_redmi-router-ac2100_openwrt_mesh
