# ros_slam_navigation
The ros slam and navigation stack test on youbot

# running commits
roslaunch youbot_gazebo_robot youbot_base_only.launch
roslaunch youbot_navigation_global 2dslam.launch
roslaunch youbot_navigation_global move_base_global.launch
rosrun gazebo_ros gazebo
rosrun rviz rviz
rosrun teleop_twist_keyboard teleop_twist_keyboard.py

