# AprilTag

```
sudo apt-get install ros-noetic-apriltag
cd ~/catkin_ws/
catkin_make
cd src/
git clone https://github.com/RMsu233/aprilTag.git
cd ..
source devel/setup.bash
roslaunch usb_cam usb_cam-test.launch
roslaunch apriltag_ros continuous_detection.launch
rosrun rviz rviz -d apriltag.rviz
```
