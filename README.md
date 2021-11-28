# Monte-Carlo-Localization_vs_dead_reckoning_using_Extended-Kalman-Filters

This repository implements:
1) Advanced Monte Carlo Localisation 
2) Dead reckoning using sensor fusion of IMU and Odometry data using Extended Kalman Filters.

## Steps to use the repository

1) Set up [ROS](http://wiki.ros.org/noetic/Installation/Ubuntu) (neotic preferred)
2) Set up the [ROS Navigation Stack](http://wiki.ros.org/navigation)
3) Clone this repository to (your catkin workspace)./src and run catkin_make (do not forget to source your devel/setup.bash file :D)


### Advanced Monte Carlo Localisation 
  
  Install the [amcl](http://wiki.ros.org/amcl) package using ```sudo apt install ros-noetic-amcl```  
  Maps for the turtlebot3_world and turtlebot3_house are provided in the maps folder in /turtlebot3/turtlebot3_slam
  
### Dead reckoning using Extended Kalman Filters 

  Install the [robot_localization](http://wiki.ros.org/robot_localization) package using  ```sudo apt-get install ros-neotic-robot_localization -y```

