# Connection-Check

This Python script is a ROS (Robot Operating System) node that checks the network connection between any two devices ex. Robot and remote server.

**Prerequisites**

Before using this code, make sure you have the following installed:

1. ROS (Robot Operating System) - [Installation Guide](https://wiki.ros.org/Installation).

**Setup**

1. Clone this repository to your ROS workspace:

   ```bash
   git clone https://github.com/MadushankaHP/Connection-Check.git
   
2. Build the ROS workspace:
   ```bash
   cd your_ros_workspace
   catkin_make
   source devel/setup.bash

**Usage**

Launch the connection check node:
   ```bash
   roslaunch connection_check network.launch
   ```
The script will continuously check the network connection and ROS master status and publish the result to the **/connection** topic.
**Notes**

Make sure to replace **192.168.8.125** with the actual IP address you want to ping in the **remote_host** variable.


