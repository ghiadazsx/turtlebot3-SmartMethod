# turtlebot3-SmartMethod
here is the second task for AI and Robotic in this task sprate in two part the first part is for install turtlebot3 and run the the turtle in empty world in Gazebo and the second part is to Use SLAM
### PART ONE (install Turtlbot3 )
1. install ROS 
2. make sure you install all the dependency of turtlebot3 in same directory to avoid all the errors
3. from here you download the dependency [turtlebot3.com ](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup)
4. change the directory to create catkin_make by using this commend `cd ~/catkin_ws
5. then write an catkin_make to run all the dependency correctly 
6. make sure to install gazebo dependency and python dependency in `cd ~/catkin_ws/src`
7. for gazebo (`sudo apt-get install ros-kinetic-gazebo-ros.`) and for sure do these commend after `sudo apt update` , `sudo apt upgrade`
8. for Python dependency `sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential` ,` sudo apt install python3-rosdep`,`sudo rosdep init` , `rosdep update` 
9. then do these comand `export TURTLEBOT3_MODEL=burger` , `roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch` , `roslaunch turtlebot3_gazebo turtlebot3_world.launch`
10. and BOOM everthing show up 
 ### Turtle World
 ![turtle_world](https://user-images.githubusercontent.com/40144145/125178184-f097a900-e1ea-11eb-98e1-d3d28211c40f.PNG)
### Empty World
![empty_world](https://user-images.githubusercontent.com/40144145/125178162-d2ca4400-e1ea-11eb-9525-55492096fb59.PNG)
# PART TWO (Slam and maping )
