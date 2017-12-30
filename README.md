# robosys2017_assignment1
RaspberryPi3での簡単なGPIO制御
# Demo
[raspberrypiでLEDを光らせる](https://youtu.be/UoTKK444kJM)
# Requirement
+RaspberryPi3
+linux kernel sorce
  +`/usr/src/linux`をダウンロード
  +kernel build scripts:https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts
  
+LED
+抵抗器(10Ω)

#Circuit
photo
#Usage
+LEDを光らせる
`echo 1 > /dev/myled0`
+LEDを消す
`echo 0 > /dev/myled0`
+SUSHIを大量に表示させる
`cat /dev/myled0`
