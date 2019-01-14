# Robosys2018
ロボットシステム学2018の課題2
ROSを利用してLEDをブラウザから点灯させるプログラム

## 作成したプログラムについて
### 使用方法
```
sudo apt install ros-kinetic-rosbridge-suite
roscore
roslaunch rosbridge_server rosbridge_websocket.launch
rosrun mypkg webserver.py
rosrun mypkg led_controle.py
```
### 操作について
webserver.pyを起動しブラウザにて [Raspberry piのIP]:8000 
にアクセスするとLED SWITCHの画面が表示される  
各LEDのボタンをクリックするとRaspberry piのGPIOに接続されている
LEDが点灯し, ALL LED OFFをクリックするとすべてのLEDが消灯する

## 動画URL
作成したプログラムの動画  
https://www.youtube.com/watch?v=N2Gm_YT7YZw
