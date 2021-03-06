# ESP32-Mini-DRV
一个极其简便的大电流PWM波驱动器，可以给电机，TEC等提供选择

![image-20201108173331463](http://pseven.lyhlyhl.top/image-20201108173331463.png)

一直以来arduino都是作为一款上手快，开发迅速，拓展库多而出名的主控，但是也面临着性能低下的缺点。ESP32能完美的解决这一点问题，其最高140MHZ的主频，能带来极高的性能。而且自带蓝牙和wifi使其多了很多可能性。

基于以上想法，该项目提出了一个Mini的esp32开发PWM驱动的模块，该模块分为俩个部分，分别为主控和电机驱动。为了避免主驱一体设计时，由于板子损坏而导致的更换修复费时，常常坏一小块，就得全部更换的弊端。提出主驱分离，并以XT-30做插拔式的设计。

利用ESP32 + Arduino的高速开发，能快速对多种传感器进行拓展，只要流出合适的接口即可。并且wifi和蓝牙，对于入门学习，手机操控等也是极为方便的一种选择。

该项目目标以完成如下几点：

1.能快速提供小车入门学习平台。

2.能提供足够高的性能，能给飞卡等高水平竞赛提供可使用的选择。

3.能不止于电机提供更多设备驱动支持，如TEC。

4.能将物联网的思想带入驱动器，外接各类传感器，能实现实时反馈的各项数据。当后期接入GPRS和WIFI等功能，可以实现物联网控制门帘窗帘等一切电机可以控制的。