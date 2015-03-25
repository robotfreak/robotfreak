<h1>FezBridge</h1>
FezBridge is a ABD implementation for .NETMF FEZ devices

FezBridge is an http://developer.android.com/guide/developing/tools/adb.html Android Debug Bridge (ADB) implementation in .NETMF for FEZ Devices.

<h2>Introduction</h2>

FezBridge is ported from the [http://code.google.com/p/microbridge MicroBridge] for Arduino. 
It is programmed in .NETMF and runs on FEZ devices from http://www.ghielectronics.com/ GHI electronics, like the http://www.ghielectronics.com/catalog/product/133 FEZ Domino. Other devices like http://www.ghielectronics.com/catalog/product/135 FEZ Panda] needs a small [http://ghielectronics.blogspot.com/2011/03/usb-host-support-is-added-on-fez-panda.html hardware modification to support USB host mode.


<h2>Details</h2>

At the moment FezBridge is a work in progress. The basic communication and USB enuration has been done.

ADB works on almost every Android phone. That is important if you wan't to use http://developer.android.com/guide/topics/usb/adk.html Android Open Accessory (ADK). ADK works only on Android phones with the newest firmware v2.3.4. But not all phones will support ADK, even with the newest firmware. This is where ADB can help. It has nearly the same functionality as ADK.

You can use ADB to forward TCP/IP ports via USB between phone and hardware. Simple data pipes can be used for communication. 

A description of the ADB protocol can be found http://lxr.e2g.org/source/system/core/adb/protocol.txt here.

video http://www.youtube.com/watch?v=sDUndL7bEic


<h2>To do list</h2>

 * build seperate driver class
 * Demo programs 
 * Demo apps (Android side)

<h2>Weblinks</h2>
 * https://github.com/robotfreak/robotfreak/new/master/fez-bridge FezBridge Source repository
 * http://developer.android.com/guide/developing/tools/adb.html Android Debug Bridge (ADB)
 * http://www.ghielectronics.com/ GHI electronics
 * http://code.google.com/p/microbridge MicroBridge
