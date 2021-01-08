# 
This is a kadai2 repository
# mypkg
ロボットシステム学　課題2

# １．概要  
講義内で作成したプログラムです。改造点はありません。

# ２．環境  
Raspberry Pi4(ubuntu20.04 LTS)

# ３．実装内容   
0から1ずつ加算した数値を出力

# ４．インストール・実行手順  
1 `$ catkin_ws/src/mypkg`上に
`git clone https://github.com/usuisyun/mypkg.git`を打つ  
`cd ~/mypkg/scripts`  
2 別のターミナルを開き`roscore`を打つ  
3 `chmod +x count.py`  
4 `rosrun mypkg count.py`  
5 もう一つ新たにターミナルを開き`rostopic echo /count_up`

# ５．ライセンス　　
GNU General Public License v3.0
