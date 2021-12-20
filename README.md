# robosys_2021_ros

In this package, the professor gives credit to the student according to the amount paid by the student. The number of credits that a student receives is determined by the amount paid by the student and a random number.

### Nodes

There are two nodes in this package, ```student``` and ```professor```.

- ```student```: A node for entering an amount.
- ```professor```: A node for giving credits to the received amount(USD). The number of credits to be given is as follows.
  - 0〜999: 0(Displayed as ```I will not give you any credits.```)
  - 1000〜99999: 1~3
  - 10000〜999999: 4~7
  - 100000〜: Provide enough credits to graduate.(Displayed as ```I allow you to graduate this college```)
  
The number of credits you receive is randomly determined by a random number.

# Execution environment
This package have been developed and tested on ROS Melodic. Please see below for details.

- ROS Melodic
  - OS: ubuntu 18.04 LTS
  - ROS Distribution: Melodic Morenia
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
Starting publisher, open another terminal and enter this command(```terminal1```):
```
rosrun robosys_2021_ros stu
```
Starting subscriber, open another terminal and enter this command(```terminal2```):
```
rosrun robosys_2021_ros pro
```
In ```terminal1```), 

# Note

You can't obtain credits if you pay much money to the professors.

# Author
- Chiba Institute of Technology 
  - Kippei Onishi(s18C1019UM@s.chibakoudai.jp) and Ryuichi Ueda  

# License

"robosys_2021_ros" is under [BSD 3-Clause "New" or "Revised" License](https://en.wikipedia.org/wiki/BSD_licenses).
