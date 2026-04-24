这是用stm32开发版制作遥控器固件，

开发版参数
尺寸-- 63mm x 41mm
cpu-- stm32f429bit6,主频180MHZ，使用晶振12MHZ，
sram-板带16M
RGB液晶接口-- FPC 40PIN 0.5mm间距，需要外接通用40PIN转接板来驱动背光

        

使用模块        
1.屏幕1-驱动芯片st7701s,分辨率 360X640                 
  屏幕2-驱动芯片st7625 ,分辨率 480x272

2.声音模块 5128功放模块

3.sx1281 亿佰特E28-2G4M27SX模块

4.电压检测使用1：5电子积木模块


开发板GPIO 连接
<img width="1707" height="1038" alt="Screenshot 2026-04-24 205219" src="https://github.com/user-attachments/assets/ef7a4040-1c40-40c8-8f9e-4f219aff7731" />



固件文件        
https://github.com/Steam2024/STM429BIT6-EdgeTx/blob/main/firmware-360x640.bin
