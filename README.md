# robosys2017_assignment1
RaspberryPi3での簡単なGPIO制御
## Demo
[raspberrypiでLEDを光らせる](https://youtu.be/UoTKK444kJM)
## Requirements
+ RaspberryPi3  
+ linux kernel sorce  
  + `/usr/src/linux`をダウンロード  
  + kernel build scripts:https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts  
+ LED  
+ 抵抗器(10Ω)  
## Circuit
![](https://github.com/maimurakami/robosys2017_assignment1/blob/master/IMG_01.jpg)
## Usage
+ LEDを光らせる  
`echo 1 > /dev/myled0`
+ LEDを消す  
`echo 0 > /dev/myled0`
+ SUSHIを大量に表示させる  
`cat /dev/myled0`
## Reference/Quotation
[ロボットシステム学 講義資料](https://github.com/ryuichiueda/robosys2017/blob/master/07.md)
