# turtlebot_point_key
**turtlebot3_pointop_key.py**: 控制小车前进到目标点，不会后退   
**turtlebot3_pointop_key_maple.py**: 控制小车前进/后退到目标点  
**autonav.py**： 使用程序里预定义的坐标点数组控制轨迹     

## Step1
启动一个小车模型程序，其必须可以订阅cmd_vel,必须可以发布odom（base_footprint--odom)   
*例如*  
```bash
  roslaunch turtlebot3_fake turtlebot3_fake.launch
```
*或者*
```bash
  roslaunch turtlebot3_gazebo turtlebot3_world.launch
```
## Step2
```bash
  cd .py文件路径下
  python ./turtlebot3_pointop_key.py
```
在命令行输入坐标点：   
x : position x (m)  
y : position y (m)   
z : orientation z (degree: -180 ~ 180)  
If you want to close, insert 's'    
例如***1 0.5 120***空格分割
<maintainer email="190258039@qq.com">maple</maintainer>
<git url https://github.com/MapleHan/turtlebot_point_key.git>
