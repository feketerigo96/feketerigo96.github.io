---
layout: post
title: Flash TX2 modules and install Connect BSP
date: 2020-8-11
categories: test
tags: [TX2,Connect]
descrpition: "Flash TX2 modules and install Connect BSP"
---

In order to install NVIDIA jetpack 4.x, you need to use [NVIDIA SDKManager](https://developer.nvidia.com/nvidia-sdk-manager-12). The process is showed in [this video](https://www.youtube.com/watch?v=s1QDsa6SzuQ). Remember you need to check whether TX2 is in force recovery mode. <code>lsusb</code>command can check it.

Next you should install [Connect Tech boards BSP](https://connecttech.com/resource-center/l4t-board-support-packages/). The process is showed in [this video](https://www.youtube.com/watch?v=9uMvXqhjxaQ).

After installing BSP, you need to install opencv,CUDA and other APIs. Check [this page](https://connecttech.com/resource-center/kdb374/). You should not use USB calble to do this. Use <code>ifconfig</code> command, check wlan->inet, this is the ip address.

When the installing process fails, it may be due to the bad Internet environment. Plug in the WiFi antenna, or change your Internet environment.

P.S. The Internet environment in Chiba University(or CSPC) may lead to install failure.