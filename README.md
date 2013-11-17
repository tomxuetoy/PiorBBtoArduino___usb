RaspberryArduino___usb
======================

to show how to communicate bwteen Raspberry and Arduino via usb

The original code is from below link:
http://blog.oscarliang.net/connect-raspberry-pi-and-arduino-usb-cable/

Other notice:
"Run Python 2 on Raspberry Pi. You will find this from the menu under Programming, 
you should use Python 2 not 3." by Oscar Liang


Tom Xue：
（1）通过调试串口运行如下命令无法看到结果
python usb.py

（2）但是可以在调试串口下先启动python：
python
再一行行输入python源代码，最后两次回车，开始接收Arduino通过USB发送过来的数据

（3）或者在Raspberry的图形界面下通过IDLE(python 2.7.3)运行之。
python usb.py
