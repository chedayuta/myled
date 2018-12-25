# Device driver for Raspberry Pi 
ロボットシステム学 課題1
Raspberry Pi用に作成したデバイスドライバを用いて2つのLEDの点灯、消灯を行う。
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3YOIyL8mGE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## How to use


0～3の値を書き込むと以下の通りGPIOの動作が切り替わる。
GPIO24が左の黄色いLED、GPIO25が右の赤いLEDとなっている。
0 : GPIO 24 OFF, GPIO 25 OFF
1 : GPIO 24 ON,  GPIO 25 OFF
2 : GPIO 24 OFF, GPIO 25 ON
3 : GPIO 24 ON,  GPIO 25 ON

