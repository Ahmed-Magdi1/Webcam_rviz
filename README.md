## Webcam_Rviz

```
$ sudo apt-get install ros-noetic-usb-cam
```


```
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

# To see the camera in RViz
```
$ rosrun rviz rviz
```
then add the camera and add the camera topic "/usb_cam/image_raw"


