iOS-SDK

AXABeacon SDK

一.概述

开发包（SDK）符合苹果的iBeacon技术，提供了扫描或管理Beacon设备或模拟iBeacon设备的API。你可以访问AXAET官网（http://www.axaet.com）了解更多信息.

二.开发

1.将SDK的框架目录导入到您的工程中 将下载的SDK文件解压，拖动里面的SDK.Framework到工程中，而不是整个文件.

2.拖到工程中后，弹出以下对话框，勾选"Copy items into destination group's folder(if needed)"，并点击“Finish“按钮

3.整个解压包包含演示demo，请参考。

4.特别强调，iBeacon监测要在info.plist文件中添加，NSLocationAlwaysUsageDescription key值 或者 NSLocationWhenInUseUsageDescription key值。