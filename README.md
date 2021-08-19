# ArUco_EKF_SLAM

Prerequisites
---

OpenCV 3.1, Eigen, ROS

Demo
---
Step1. Download the repository to your ROS workspace: catkin_ws/src

Step2. Make: catkin_make

Step3: Run launch: roslaunch aruco_ekf_slam slam.launch

Step4. Play a rosbag: rosbag play aruco_slam_data_qhd1.bag -r 5

References
---
1. OpenCV library for the fundamental functions of Aruco codes: https://docs.opencv.org/3.3.0/d9/d6d/tutorial_table_of_content_aruco.html

2. Probalisitic Robotics  -- by Thrun, S., Burgard, W., Fox, D. The MIT Press (2005) PDF version: 

