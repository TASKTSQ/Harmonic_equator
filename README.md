# Harmonic_equator  
Harmonic_equator Based on OnsetpX  
基于OnsteX控制的轻量化14-100双轴谐波赤道仪  
由于GitHub不能上传大文件，模型上传于拓竹的MakerWorld  
模型地址：  
https://makerworld.com.cn/zh/models/751859#profileId-716504  

Bilibili专栏：  
https://www.bilibili.com/opus/1013653427665764407  

此处主要是存放PCB加工文件  
可直接用于立创商城免费打样  
PCB基于Onstep官网的MaxESP4精简设计仅保留双轴电机 更改为Type-C数据接口  
程序基于OnstepX 需要基于原版OnstepX修改MaxESP4 的引脚定义  
驱动使用TMC2209 UART版本 最大细分256  
Onstep官方站：  
https://onstep.groups.io/g/main  

关于程序 在/Firmware文件夹内:  
Firmware mods from OnstepX    
Replace The Pins.MaxESP4.h to the Raw OneStep Path ：\OnStepX\src\pinmaps    
Modifing The Config.h and Extended.config.h or just Replace  
基于OnstepX修改  
请将Pins.MaxESP4.h替换到OnstepX的目录：：\OnStepX\src\pinmaps    
自行修改The Config.h 和 Extended.config.h 或者直接替换使用  
  
！！！本开源不可用于商业目的！！！  
