# ros2-yolo-debris-detection
ros2-yolo-debris-detection is a ROS2 based proof of concept which uses LiDAR and 3D camera data to achieve real time detection of orbital debris using both standard YOLO and 3D-YOLO models.
This project is modelled to mimick onboard perception of a low Earth orbit satellite focusing on maintaining functionality across a simplified combination of lighting conditions and distances.

## System Overview
- **3D depth camera** (Orbbec Gemini 335L)
- **2D LiDAR System** a 2D Lidar sensor with vertical actuation to give a full 3D FOV
- **YOLO** for RGB based object detection
- **3D-YOLO** for point-cloud based object detection
- **ROS2 (Humble)**

The goal is to create a power efficient, effective system in a scaled physical test bed. 

## Dependencies

This project uses the following libraries and wrappers:
 
- **ROS2 Humble** - https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html
- **Orbbec Gemini 335L ROS2 Wrapper** – https://github.com/orbbec/OrbbecSDK_ROS2.git
- **Slamtec RPLIDAR** - https://github.com/Slamtec/rplidar_ros
- **Python**
- **OpenCV**
