# wechat-miniprogram
WeChat miniprogram, one of the miniprograms, is an application that can be used without downloading and installing, the development of which requires html5, css and javascript.
#### Overview

​		This miniprogram is developed for the IoT device that I designed before. The system is to collect data, save these data, visualize the data and perform some easy analysis.

#### Receive the data

​		This miniprogram receives data through BLE(Bluetooth Low Energy), such as jdy-16. It can receive data concerning temperature and other kinds of data about ones' sleeping.
#### Save the data

​		The received data will be saved in the cloud in order for further query and analysis.

#### Visualization

​		The APP can visualize the data immediately through wx-charts.


#### News delivery

​		The latest news will be shown.


### 微信小程序-功能介绍

#### 总览

​		该小程序是为配合蓝牙电子设备而开发的，主要功能是接受数据，存储数据，可视化数据和一些简单的数据处理与分析。

#### 接收数据

​		微信小程序支持低功耗蓝牙（BLE）的数据传输功能，例如jdy-16蓝牙。本产品主要接受距离数据和温度数据。

#### 存储数据

​		接收到的数据存储到微信云数据库中，便于后续提取、分析。

#### 可视化数据

​		借助wx-charts，将收到的数据实时可视化。

#### 数据分析

​		1.通过距离数据计算离群值，判断翻身次数。

​		2.将温度数据视为时间序列，通过计算自相关系数和偏自相关系数判断其平稳性。

#### 新闻推送

​		利用scroll-view显示推送的新闻。
