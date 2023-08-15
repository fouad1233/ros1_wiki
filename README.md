# Forked from ROS1 Wiki 

## ROS mobile robot URDF Part#1 notes

- Create package command
  
```bash
    cd r1_wiki_ws/src/ros1_wiki
    catkin_create_pkg mobile_robot std_msgs rospy
```
- Make the new package
```bash
    cd r1_wiki_ws
    catkin_make
```
- Don't forget to source files using
```bash
    source 'r1_wiki_ws/devel/setup.sh' 
```
- To launch the code run the command above 
```bash
    roslaunch mobile_robot rviz.launch
```
- To instal ros-noetic-joint-state-publisher-gui
```bash
    sudo apt-get install ros-noetic-joint-state-publisher-gui
```
