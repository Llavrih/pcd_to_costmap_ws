# Dual-Camera Costmap with Pointcloud2
Costmap Setup for Two RealSense Cameras

Welcome to the dual-camera costmap workspace. Familiarize yourself with `params.yaml` and `pointcloud2_to_costmap.launch`. 

Both cameras' transformations must be set in these files for accurate costmap generation from their combined point cloud data. Adjust the parameters in `params.yaml` for both cameras and ensure the `pointcloud2_to_costmap.launch` matches your robot and camera setup for precise navigation.

![ezgif com-video-to-gif](https://github.com/Llavrih/pcd_to_costmap_ws/assets/99958904/8b42b025-c027-49e9-8e47-0f3ccb3ebd79)

# Rtabmap

RTAB-Map visual odometry with Intel RealSense D435: The GIF below illustrates the integration of depth and color data for accurate 3D mapping and navigation.

![ezgif com-video-to-gif(1)](https://github.com/Llavrih/pcd_to_costmap_ws/assets/99958904/e0e50dd5-f3bc-419e-a2bb-666acdd0439a)
