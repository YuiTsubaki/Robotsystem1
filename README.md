#2020年　ロボットシステム学課題１<br>

##実験目的・概要<br>
RaspberryPi4を利用してデバイスドライバを作成し、LEDを光らせるプログラム<br>

##利用したもの<br>
RaspberryPi4とそれに付随する周辺機器、LED、ブレッドボード、抵抗（200Ω）、ジャンパーピン<br>

##プログラムの内容<br>
・echo 1 > /dev/myled0　で実行：LEDが点灯<br>
・echo 0 > /dev/myled0　で実行：LEDが消灯<br>

##回路<br>
GPIO25とGNDの間にLEDと抵抗を接続し、LEDのアノードをGPIO25に接続しGNDへ<br>

回路について教えてくれた人<br>
tadanohiroyuki<br>
