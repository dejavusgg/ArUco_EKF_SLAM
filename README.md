# ArUco_EKF_SLAM

Dataset for the demo: https://pan.baidu.com/s/10crRfgGcZ-XgcBjefxAPDg     Password: pqby

After you download the dataset, the launch file (slam.launch) should be modified to link the correct download path.

You can also have a basic idea of the overall effect of this SLAM project by taking a look at the pre-recoreded animation (ekf.gif). 

Prerequisites
---

OpenCV 3.1, Eigen, ROS

Demo
---
Step1. Download the repository to your ROS workspace: catkin_ws/src

Step2. Make: catkin_make

Step3: Run launch: roslaunch aruco_ekf_slam slam.launch

Step4. Play a rosbag: rosbag play aruco_slam_data_qhd1.bag -r 5

![aruco_ekf_slam_gif](https://user-images.githubusercontent.com/85860671/153775051-1f493f74-f297-4429-ab6b-63b8ffa021af.gif)


References
---
1. OpenCV library for the fundamental functions of Aruco codes: https://docs.opencv.org/3.3.0/d9/d6d/tutorial_table_of_content_aruco.html

2. Probalisitic Robotics  -- by Thrun, S., Burgard, W., Fox, D. The MIT Press (2005) 

