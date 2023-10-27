# Costmap with Pointcloud2
Creating a Costmap with a RealSense Camera Workspace

Welcome to the workspace dedicated to generating a costmap using a single RealSense camera. The primary configuration files you need to be familiar with are `params.yaml` and `pointcloud2_to_costmap.launch`.

In these files, you'll define the essential transformations between the map frame and the camera frame. It's crucial to set these transformations correctly to ensure accurate costmap generation based on the camera's point cloud data.

Make sure to review and adjust the parameters in params.yaml as needed, and ensure that the transformations in pointcloud2_to_costmap.launch align with the physical setup of your robot and camera. Proper configuration will ensure that the costmap represents the environment accurately and aids in reliable robot navigation.
![costmap_test](https://github.com/Llavrih/pcd_to_costmap_ws/assets/99958904/00606da2-c1cb-41ea-bd50-2136d6f244ee)
