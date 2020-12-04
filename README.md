2020年　ロボットシステム学課題１\n

実験目的・概要\n
RaspberryPi4を利用してデバイスドライバを作成し、LEDを光らせるプログラム\n

利用したもの\n
RaspberryPi4とそれに付随する周辺機器、LED、ブレッドボード、抵抗（200Ω）、ジャンパーピン\n

プログラムの内容\n
・echo 1 > /dev/myled0　で実行：LEDが点灯\n
・echo 0 > /dev/myled0　で実行：LEDが消灯\n

回路\n
GPIO25とGNDの間にLEDと抵抗を接続し、LEDのアノードをGPIO25に接続しGNDへ\n

教えてくれた生徒\n
tadanohiroyuki\n
