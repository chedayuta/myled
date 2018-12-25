# Device driver for Raspberry Pi 
ロボットシステム学 課題1
Raspberry Pi用に作成したデバイスドライバを用いて2つのLEDの点灯、消灯を行う。

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/C3YOIyL8mGE/maxresdefault.jpg)](https://www.youtube.com/watch?v=C3YOIyL8mGE)  
[デモ](https://www.youtube.com/watch?v=C3YOIyL8mGE)


## How to use


0～3の値を書き込むと以下の通りGPIOの動作が切り替わる。
GPIO24が左の黄色いLED、GPIO25が右の赤いLEDとなっている。
0 : GPIO 24 OFF, GPIO 25 OFF
1 : GPIO 24 ON,  GPIO 25 OFF
2 : GPIO 24 OFF, GPIO 25 ON
3 : GPIO 24 ON,  GPIO 25 ON

