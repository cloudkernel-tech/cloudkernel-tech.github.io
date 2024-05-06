# Kerloud Mini 自驾仪

<p align="center">
<img src ="../../assets/kerloud_mini/kerloud.png" width = 550/>
</p>

Kerloud mini是云讷科技于2019年发布的第一款飞控产品，它的设计遵循Pixhawk FMUv3硬件标准。

## 产品特性

（1）接口优化，尺寸小巧，尽可能去掉了不常用的接口

（2）多冗余度传感器设计，IMU全部采用高性能的ICM传感器系列

（3）接口具备可拓展性，可同时接入数传和上位机电脑，具备复杂任务开发功能，同时增加debug口，方便深度用户调试

（4）硬件接口实现全方位静电防护，相对于同类产品提升了安全性能

（5）人机交互优化，主呼吸灯和解锁指示灯外置于GPS模块，使无人机状态一目了然

（6）专业CNC铝制飞控外壳，增加抗干扰能力，散热能力强，外观稳重大方

（7）提供长期稳定软硬件支持，坚持开源软件风格，提供行业方案定制服务

## 指标

| 部件 | 指标 |
| :--: | :--: |
| 主处理器 |   STM32F427 Cortex M4, 2MB flash, 168 MHz |
| 协处理器 |  STM32F100 Cortex M3, 64KB flash, 24MHz |
| 加速度计 |   ICM42670P, BMM088 (v2) <br> ICM20602, ICM20689 (v1) |
| 陀螺仪 |  ICM42670P, BMM088 (v2) <br> ICM20602, ICM20689 (v1) |
| 磁感计 |  IST8310 (外置), BMM150 (内置)  (v2) <br> IST8310 (内置), QMC5883（外置） (v1)  |
| 气压计 | BMP388 (v2) <br> ms5611 (v1) |
| Kerloud GPS 模块 |  Ublox M8N GPS，外置磁感计 |
| 供电电压 |  Power port: 4.75V~5.5V, <br> USB port: 4.75V~5.25V, <br> 自带分电板: 2~6S, <br> 最大传感电流 90A, <br> BEC: 5.3V, 最大连续电流 3A |
| 工作温度范围 | -20 ~ 60 度|
| 外壳| CNC 铝制外壳 |
| 尺寸 | 57mm \* 45mm \* 14.6mm |
|重量 |Kerloud Mini Autopilot: 40g  <br> Kerloud GPS: 30g |

## 开箱说明

<p align="center">
<img src ="../../assets/kerloud_mini/Kerloudmini_resized.jpg" width = 500/>
</p>

<p align="center">
<img src ="../../assets/kerloud_mini/kerloud_pkgview.jpg" width = 500/>
</p>

我们提供的完整Kerloud Mini包装包含下述零配件：

| 零配件 | 数量 |
| :--: | :--: |
| Kerloud Mini飞控 | 1 |
| Kerloud GPS定位模块 | 1 |
| 分电板 | 1 |
| USB线 | 1 |
| I2C 拓展板 | 1 |
| 线材套件 | 1 |
| 8G内存卡 | 1 |
| 产品小册 | 1 |

## 接口示意

<p align="center">
<img src ="../../assets/kerloud_mini/kerloud_interface_p1.png" width = 500/>
</p>

<p align="center">
<img src ="../../assets/kerloud_mini/kerloud_interface_p2.png" width = 500/>
</p>

## 如何购买

中国大陆用户可以前往我们官方淘宝店铺购买：

<https://item.taobao.com/item.htm?id=622263169337>

其他地区用户可以咨询当地代理商或者发邮件给我们．