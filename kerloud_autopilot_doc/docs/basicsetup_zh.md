# 基本设置

Kerloud自驾仪在出厂时已经加载了基于V1.10.0的px4稳定软件，并会持续更新，大部分用户可以直接上手使用．

基本的设置步骤可以参考：<https://dev.px4.io/master/en/setup/config_initial.html>．主要步骤说明如下，可以通过[QGroundControl](http://qgroundcontrol.com/)轻松操作：

## 机型选择

<p align="center">
<img src ="../assets/airframe_setting.png"/>
</p>

用户可以选择不同的机型，包括多旋翼，固定翼，无人车和其他布局的设备．选择之后点击右上角的"Apply and Reset"重启，可以设置好默认参数．

## 传感器校准

<p align="center">
<img src ="../assets/sensor_calib.png"/>
</p>

对于磁感计，陀螺仪和加速度计，都需要校准，注意点如下：

建议用户将GPS模块连接到飞控后再执行校准操作，这样可以同时校准外部和内部的磁感计．外部的磁感计安装在GPS模块上．

在陀螺仪校准中，需要保持绝对的静止．因为微小的运动会导致校准失败或者陀螺仪偏差很大．

加速度计的校准建议在水平桌面或垂直墙面完成，手持的校准方法不推荐．

## 遥控器校准

<p align="center">
<img src ="../assets/radio_setting.png"/>
</p>


用户可以选择右手油门（模式１，日本手）或者左手油门（模式２，美国手）进行遥控器设置．

## 飞行模式设置

<p align="center">
<img src ="../assets/flightmode_setting.png"/>
</p>

用户需要分配一个遥控器通道（如通道５）用于设置飞行模式．对于大部分用户，至少需要设置STABILIZED(手动自稳），POSITION(半自动)，MISSION(全自动）三种模式．高级用户可以设置OFFBOARD（在线控制）模式．

## 电源参数校准

<p align="center">
<img src ="../assets/power_calib.png"/>
</p>

电源参数的设置是用于电池状态的检测．用户需要输入电池的Cell数目，同时测量电池电压值用于校准．