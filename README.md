
# Robot Teleoperation
Simulated a remotely (keyboard) operated differential drive robot using Gazebo. 

## Demo

[![demo video](https://raw.githubusercontent.com/pratinavmongia/teleOperation/main/teleOp_Demo_thumbnail.png)](https://raw.githubusercontent.com/pratinavmongia/teleOperation/main/teleOp_Demo.mp4)

## Installation

1. Clone the repository to your ROS2 workspace
```bash
git clone https://github.com/pratinavmongia/teleOperation.git
```
2. Build the ROS2 package
```bash
cd tele_op
colcon build --symlink-install
source install/local_setup.bash
```
3. Launch the robot in RVIZ2 
```bash
ros2 launch tele_op display.launch.py
```
4. Launch the robot in Gazebo 
```bash
ros2 launch tele_op gazebo.launch.py
```
5. Open another terminal and use the command
```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard
``` 
Move the robot around

    
