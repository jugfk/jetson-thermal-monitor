# 젯슨나노 온도 모니터

젯슨나노의 모듈타입 온도센서 출력하기

<img src="./jetson_temp_monitor.gif" alt="Screenshot" title="Screenshot">

# 설치하기
```
sudo apt update
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
sudo apt install python3-pip
sudo pip3 install numpy
sudo pip3 install matplotlib
```

# 구동하기
```
git clone https://github.com/jetsonworld/jetson-thermal-monitor.git
cd jetson-thermal-monitor
$ python3 jetson_temp_monitor.py
```

# 노트
- This script is tested on NVIDIA Jetson Nano Developer Kit only.

# 출처
https://github.com/tsutof/jetson-thermal-monitor
