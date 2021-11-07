If you do not have a workspace, follow this tutorial: 
Installing and Configuring Your ROS Environment - http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment

# To add this package to your workspace

Open terminal and navigate to src folder in your catkin workspace :
```
cd ~/catkin_ws/src
```
Download the package inside this folder :
```
git clone https://github.com/anacaoliveira/IMARC-Control/pid_controller/
```

Now return to the catkin workspace and build it to get all changes saved :
```
cd ~/catkin_ws
catkin_make
```
Another option is to dowload the folder, navigate through the file explorer and find the src folder. Move the pid_controller folder to your src folder.

Once it is completed return to terminal & do the following:
```
cd ~/catkin_ws
catkin_make
```
