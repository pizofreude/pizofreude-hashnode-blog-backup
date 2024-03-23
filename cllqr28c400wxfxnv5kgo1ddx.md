---
title: "Solving Apple AirPods Connectivity Issues with Windows 10/11"
seoTitle: "AirPods connectivity to windows"
seoDescription: "How to solve AirPods connectivity problems with Windows machine"
datePublished: Sun Jan 15 2023 09:20:09 GMT+0000 (Coordinated Universal Time)
cuid: cllqr28c400wxfxnv5kgo1ddx
slug: solving-apple-airpods-connectivity-issues-with-windows-1011
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692977447261/e1caf465-0ba4-478f-8525-6522757d6802.jpeg

---

Are you having trouble connecting your Apple AirPods to your Windows 10 devices? You’re not alone. Many users have reported connectivity issues when trying to pair their AirPods with non-Apple devices. However, don’t despair — there are ways to fix this problem.

## Applicable To

These connectivity fix should applies to the following Apple AirPods models:

* AirPods 2nd Generation
    
* AirPods 3rd Generation
    
* AirPods Pro
    
* AirPods Pro 2nd Generation
    
* AirPods Max
    

## The Guide

Here’s a step-by-step guide on how to solve the Apple AirPods connectivity problem with Windows 10/11 devices:

* First, update the network adapter driver for Bluetooth and wireless services. This can be done by searching for the exact network card model on [intel.com](https://www.intel.com/content/www/us/en/homepage.html). For example, the network card model is Intel Dual Band Wireless-AC 7260.
    
* After updating the driver, restart your computer.
    
* Next, go to the Control Panel and select Administrative Tools.
    
* In Administrative Tools, select Services.
    
* In the Services (Local) tab, look for “Bluetooth Support Service”.
    

![Services.msc](https://cdn.hashnode.com/res/hashnode/image/upload/v1692977443510/0c17a40d-c882-4582-8a35-e9aaaf964939.png align="center")

* Right-click on “Bluetooth Support Service” and select its properties.
    
* Under “Startup type”, change it from “automatic” to “manual” and hit apply and OK.
    
* Right-click on “Bluetooth Support Service” again and hit stop. Wait a few seconds, then start it again.
    

![Bluetooth Support Service Properties](https://cdn.hashnode.com/res/hashnode/image/upload/v1692977445328/259e5264-8a4c-44ab-b728-6881a086f7f6.png align="center")

* In the taskbar, go to Start — Settings — Devices — Add Bluetooth or other devices — Bluetooth. Wait until the AirPods is discovered. Move the AirPods around to help the network card find them.
    

## Disclaimer

This fix will only works if your device comes with Bluetooth 4.0 and above only. Otherwise, you need to upgrade your network card for example Intel AX210 that supports WiFi6E and Bluetooth 5.3. Cheaper alternative would be the standalone USB Bluetooth 5.3 Dongle Adapter.