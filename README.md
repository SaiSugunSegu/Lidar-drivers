# Lidar-drivers
Customized Velodyne and Ouster Drivers for Multi Lidar Integration


- Velodyne and Ouster ROS Drivers are modified to be compatible with Multiple Lidar Connectivity and Communication. 
- All these Lidar frame are given External Transformation (Extrinsics) w.r.t Single Navigation Frame.
- Can use Rviz or FoxGlove to visualize multiple lidars from single frame of refrenece.

Note: Velodyne Lidars (VLP16, VLP32, VLP128) and Ouster Lidars are used while experimenting with modifing 
Velodyne Driver: https://github.com/ros-drivers/velodyne
Ouster Driver: https://github.com/ouster-lidar/ouster_example
