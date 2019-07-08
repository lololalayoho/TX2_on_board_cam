# for Jetson 4.2+ Users.
This package is only for jetson 4.2 users. not for jetson 3.x!

`nvcamerasrc` is deprecated in jetson 4.2, so you should replace it by 'nvarguscamerasrc'!

# on_board_cam
ROS package that launches Jetson TX2 on-board camera  
Output topics:  
`/bottom/camera/image`  
`/bottom/camera_info`  
Built on top of [jetson-inference](https://github.com/dusty-nv/jetson-inference) gscamera.  

## Usage  
- `roslaunch on_board_cam bottom.launch` after successfully compiles under your catkin workspace  

## Compiling dependencies  
- ROS(built on Kinect, not tested on other distro yet)    
- OpenCV  
- CUDA Library  
- gstreamer  
