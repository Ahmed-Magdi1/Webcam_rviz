# Webcam_Rviz


### install the ROS usb_cam
```bash
$ sudo apt-get install ros-noetic-usb-cam
```
```bash
$ mkdir catkin_ws

$ cd catkin_ws

$ mkdir src

$ cd src

$ git clone https://github.com/Ahmed-Magdi1/Webcam_rviz.git

$ cd ..

$ catkin_make

$ source devel/setup.bash 

$ roslaunch cam cam.launch 
```

### To see the camera in RViz
```bash
$ rosrun rviz rviz
```
then add the camera RViz and add the camera topic "/usb_cam/image_raw"


