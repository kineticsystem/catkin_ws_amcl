ROS

For this project I've installed ROS Noetic on a Linux Xubuntu 20.04. The Virtual
Image provided by Udacity is unusable and it is not possible to setup a GPU 
passthrough device.


QTCREATOR IDE

To write the required nodes in C++, I've installed QtCreator with ROS plugin.
The following file have been created by QtCreator IDE.


BLENDER

The chassis has been modelled with Blender 2.92.0.


OPENCV

In the development of process_image node I decided to use OpenCV which may come
in handy at a later stage.


CMAKE

I found a difference in what I've learned in the course and what I've seen in ROS
Noetic. The following lines are not necessary:

#add_dependencies(drive_bot drive_bot_generate_messages_cpp) # Auto generated file.
#add_dependencies(process_image process_image_generate_messages_cpp) # Auto generated file.

