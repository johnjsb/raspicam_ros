# Raspicam_ros
Indigo ROS node for mipi camera module of Raspberry Pi

git clone https://github.com/raspberrypi/userland.git /home/pi/userland
Then use buildme to build. It requires cmake to be installed and an arm cross compiler.

source /opt/ros/indigo/setup.bash

cd /home/pi/catkin_ws/src
git clone https://github.com/dganbold/raspicam_ros.git

cd ..
catkin_make

source devel/setup.bash

Then you can run the node using launch file 
roslaunch raspicam raspicam_run.launch

