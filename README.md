2020年　ロボットシステム学課題１

実験目的・概要
RaspberryPi4を利用してデバイスドライバを作成し、LEDを光らせるプログラム

利用したもの
RaspberryPi4とそれに付随する周辺機器、LED、ブレッドボード、抵抗（200Ω）、ジャンパーピン

プログラムの内容
・echo 1 > /dev/myled0　で実行：LEDが点灯
・echo 0 > /dev/myled0　で実行：LEDが消灯

回路
GPIO25とGNDの間にLEDと抵抗を接続し、LEDのアノードをGPIO25に接続しGNDへ

教えてくれた生徒
tadanohiroyuki
