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
1 `roscore`を打つ  
2 新たにターミナルを開き`$ catkin_ws/src/mypkg`上に
3 `git clone https://github.com/usuisyun/mypkg.git`を打つ  
4 `cd ~/mypkg/scripts`    
5 `chmod +x count.py`  
6 `rosrun mypkg count.py`  
7 もう一つ新たにターミナルを開き`rostopic echo /count_up`
# ５．デモ動画  

# ６．ライセンス　　
GNU General Public License v3.0
