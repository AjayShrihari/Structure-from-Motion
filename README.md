# Structure-from-Motion
Algorithms relating to Structure from Motion 

### Camera Modelling and Transformation
* Lidar-Camera fusion 
* Drawing 3-D bounding boxes
* Detecting April Tags using 2-D Direct Linear Transform, i.e, Zhang's Algorithm for camera calibration.

[Link](https://github.com/AjayShrihari/Transformations-and-Camera-Modelling)

### Epipolar Geometry
* Plotting epipolar lines of two images and their corresponding points, and computing the location of their epipoles. Done by exerting epipolar constraints. Forms the building block of Stereo vision in Photogrammetry.

* Two view reconstruction along with random sampling consensus for a scene, written in MATLAB.

[Link](https://github.com/AjayShrihari/Two_view_reconstruction)

### PnP resection with Levenberg Marquadt Optimization
Recover pose using an iterative Perspective n point algorithm given a reconstructed scene by finding 2D-3D correspondences. 

[Link](https://github.com/AjayShrihari/PnP-Levenberg-Marquadt)

### Visual Odometry
Recovering egomotion based on monocular camera input of an agent. Takes in scenes from KITTI dataset and outputs an accurate plot of the path taken.

[Link](https://github.com/AjayShrihari/Visual-Odometry)

### Stereo vision
* Stereo vision by generating disparity maps using Stereo Global Block Matching Algorithm, and using a publisher-subscriber in ROS (written in rospy) for generating unscaled point clouds using ROS Octomap server.

[Link](https://github.com/AjayShrihari/Stereo-Algorithms)
* Generating dense 3D point cloud reconstruction of a scene from stereo images. Includes block matching along with point cloud registration to produced scaled point clouds that can be rendered in Open3D.

### EKF Localization
Given a sensor model along with observations of landmarks in a scene, estimating the 2D pose of a robotby using an Extended Kalman Filter (EKF). Prediction and update steps included along with the Jacobians used for calculation for the given sample problem.

[Link](https://github.com/AjayShrihari/EKF-Localization)

### Trajectory planning
Polynomial based trajectory planning, using quintic polynomials and bernstein polynomial. Implementation of obstacle avoidance shown in a toy example.

[Link](https://github.com/AjayShrihari/Polynomial-trajectory-planning)

### Frenet frame based Obstacle Avoidance
Coming soon!

#### Note:
Done in collaboration with [Chaitanya Kharyal](https://github.com/kharyal) 
