# 3-Channel-signal-amplifier
This is a 3 Channel signal amplifier,you can use it to amplifier small signal from mcu.For example,you can amplify a pwm signal to control LED stripe or drive a DC brushed motor



## 项目简介
这是一个信号放大模块，采用类似于单片机开漏输出的方案，将MCU输出的信号通过NMOS进行放大，可用于有刷直流电机驱动、共阳极LED灯带调光等场景。

PCB采用嘉立创EDA绘制，PCB工程文件见ProPrj_Signal_Amplifier_2025-09-20.epro


## 项目参数
* NMOS采用UMS AO3400A，驱动部分最大电流可达5A，采用了续流二极管等完整的电路保护措施


## 原理解析（硬件说明）

### LAYOUT

![LAYOUT布局](https://cdn.jsdelivr.net/gh/Yan-Haiyang-Tju/PicGO_Reposity/20250920020429060.png)

### 3D

![3D](https://cdn.jsdelivr.net/gh/Yan-Haiyang-Tju/PicGO_Reposity/20250920020454628.png)
