---
layout: device
title:  "Nubia ZTE Z17"
codename: nx563j
downloadfolder: nx563j
supportstatus: Current
maintainer: youyim
oem: Nubia
devicetree: https://github.com/TeamWin/android_device_nubia_nx563j
---

{% include disclaimer.html %}

{% include supportstatus.html %}

{% include download.html %}

{% include twrpinstall.html %}

<html>
<div class='page-heading'>Installation:</div>

1.unlock bootloader

fastboot oem nubia_unlock NUBIA_NX563

2.flash twrp

fastboot flash recovery twrp.img
</html>
