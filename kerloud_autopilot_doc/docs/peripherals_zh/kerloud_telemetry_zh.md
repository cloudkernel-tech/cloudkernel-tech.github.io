# Kerloud Telemetry数传

Kerloud Telemetry是由云讷科技推出的一款面向无人系统、传输可靠的短距离无线传输电台。产品基于ISM Sub-G频段，采用FSK调制、抗干扰能力强，具备Uart/USB通用接口，支持Pixhawk/APM系列飞控，助力用户更快捷实现互连。

<p align="center">
<img src ="../../assets/kerloud_telemetry/kerloud_telemetry_pkg.jpg" width = 500/>
</p>

## 参数

| 指标 | 参数 | 备注 |
| :--: | :--: | :--: |
|工作频段| 915MHz | |
| 输出功率| 100mW（20dBm）| |
| 波特率 | 57600（默认）| |
| 传输距离 | 800m @ 64kbps 空速 | 室外空旷无遮挡环境|
| 接口 | Uart（GH1.25 4Pin）/Micro USB | |
| 供电电压 | 3.8~5.5V @ Uart, 4.75~5.25V @ USB | |
| 通信接口电压域 | 3.3V| |
| 发射工作电流 | 100mA @ 20dBm, 40mA @ 14dBm| 典型值|
| 接收工作电流 | 25mA | 典型值 |
| 工作温度 | -20~85 ℃ | |
| 产品尺寸（不含天线）| 55（长）×30（宽）×7（高） | 单位：mm|
| 重量（含天线） | 15 | 单位：g|


**备注：**
接口波特率、空速、发射功率、无线通道等参数用户可调，部分参数与距离相关。

## 产品特点

* 通信接口全方位ESD防护
* 使用高带宽CMOS模拟开关切换通道，通信稳定
* 专业射频天线匹配，保障无线性能
* 统一接口，机载、地面端可灵活互换
* 无线通道可配置，允许多个模块频分复用，互不干扰
* LED 状态指示

## 配件清单

| 部件 | 数量 |
| :--: | :--: |
| Kerloud telemetry 模块 | 2 |
|天线| 2 |
| USB连接线| 1|
| Uart连接线（GH） | 1|


## 接口定义

<p align="center">
<img src ="../../assets/kerloud_telemetry/kerloud_telem_interface.png" width = 350/>
</p>


## 如何购买

中国大陆用户可以通过淘宝链接在云讷科技官方店铺购买：

<https://item.taobao.com/item.htm?&id=690661768758>

其他地区用户可以咨询当地代理商或者发邮件给我们<cloudkerneltech@gmail.com> 。



