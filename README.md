# Quick Start
Must install the ROS Kinetic on Ubuntu 16.04 LTS 
```
$ mkdir -p ~/cadac_ws/src
$ cd ~/cadac_ws
$ catkin_make
$ cd src
$ git clone https://github.com/octoberskyTW/ros_based-sim.git
$ cd ..
$ catkin_make
$ source devel/setup.bash 

```
## Execute
```
$ roscore
$ cd ~/cadac_ws
$ rosrun next-sim dynamic_model
$ rosrun next-sim gnc_model
```
