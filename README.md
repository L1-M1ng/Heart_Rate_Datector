# Heart_Rate_Datector

> 2020秋感测综设-心电检测器

@Design by Dawn

## 1. 主要信息

1. 芯片: STM32RCT6
2. 模块: AD8232,  正点原子TFT-LCD 1.3 '
3. 软件: MDK5 

## 2.功能


1. 读取AD8232所测量到的心电信号电压，并显示在LCD屏幕。

   导联接法：

   <img src="3.Image/导联接法.jpg" style="zoom:50%;" />

   实现效果：

   <img src="3.Image/心电图显示效果.jpg" style="zoom: 33%;" />

2. 采用动态阈值法实时测量心率，实时更新。

## 3.待完成git

1. 传送数据至PC，labview显示，并发布至网页端。

