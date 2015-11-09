# barrett_model
This is a ROS package including model files for double wam arms with rack

How to run:
    1.put the barrett_model package in the src folder of your catkin workspace. 
    2.catkin_make.
    3.use roslaunch command to launch xacrodisplay.launch.

Some notification:
    1.all module components are xacroed, which makes it easier to assemble, the backbone codes of components module come 
      from [jhu-lcsr](https://github.com/jhu-lcsr), in their site are many other useful ROS resources about wam.
    2.I write and test the code on my own laptop, whose environment is Ubuntu 14.04 LTS, ROS indigo, however I think it's 
      compatible with Ubuntu12.04 LTS, ROS Hydro environment on lab computer.
    3.due to some bug the rviz may crash, you can rerun the roslaunch command, usually the rviz can open successfully after about
      4 times of reruning.
      


