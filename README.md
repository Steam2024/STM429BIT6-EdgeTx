这是用stm32开发版制作遥控器EdgeTx固件，



开发版参数        
尺寸-- 63mm x 41mm        
cpu-- stm32f429bit6,主频180MHZ，使用晶振12MHZ，        
sram-板带16M32位宽SDRAM        
RGB液晶接口-- FPC 40PIN 0.5mm间距，外接通用40PIN转接板来驱动背光    
SD卡接口        
GPIO-56个可使用IO口

开发板图片        
<img width="300" height="300" alt="300" src="https://github.com/user-attachments/assets/aa2bbcc4-abb7-440d-843a-f6ac6f99883b" />


RGB转接板
<img width="200" height="197" alt="O1CN01snn2j51RaDBhElY1p_!!3278452127" src="https://github.com/user-attachments/assets/9999484a-d117-4aa5-83ad-54fd75b0fc75" />







        

使用模块        
1.屏幕1-驱动芯片st7701s,分辨率 360X640                 
  屏幕2-驱动芯片st7625 ,分辨率 480x272

2.声音模块 5128功放模块

3.RF模块：sx1281 亿佰特E28-2G4M27SX模块

4.电压检测使用1：5电子积木模块


开发板GPIO 连接
<img width="800" height="486" alt="Screenshot 2026-04-24 205219" src="https://github.com/user-attachments/assets/6b913366-32ce-4443-a25b-ff3973b34a00" />






### 💾 本地固件

[下载 360x640屏幕 固件 (firmware.bin)](https://github.com/Steam2024/STM429BIT6-EdgeTx/raw/main/firmware-360x640.bin)        

[下载 480x272屏幕 固件 (firmware.bin)](https://github.com/Steam2024/STM429BIT6-EdgeTx/raw/main/firmware-480x272.bin)

        

        
