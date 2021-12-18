# robosys_2021_ros

This package 

# Execution environment
This package have been developed and tested on ROS Noetic. Please see below for details.

- ROS Melodic
  - OS: ubuntu 20.04 server
  - ROS Distribution: Noetic
# Install
- ROS
  - http://wiki.ros.org/melodic/Installation
- Create a [catkin](http://wiki.ros.org/catkin#Installing_catkin) workspace
  - http://wiki.ros.org/ja/catkin/Tutorials/create_a_workspace
- Clone this repository and enter it:
```
git clone git@github.com:kippei-onishi/robosys_2021_ros.git
cd ~/catkin_ws
catkin build
```
# Usage Instructions
Open a terminal and enter this command to start ROS:
```
roscore
```
Starting publisher, open another terminal and enter this command:
```
rosrun robosys_2021_ros pub 
```
Starting subscriber, open another terminal and enter this command:
```
rosrun robosys_2021_ros sub
```
# Commands


# Note

Please connect resistors to the LED's to prevent them from bursting.

# Author
- Chiba Institute of Technology 
  - Kippei Onishi(s18C1019UM@s.chibakoudai.jp) and Ryuichi Ueda  

# License

"robosys_2021_ros" is under [BSD 3-Clause "New" or "Revised" License](https://en.wikipedia.org/wiki/BSD_licenses).
