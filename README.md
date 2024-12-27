**Requirements:**

Ubuntu 22.04.5 LTS , ROS 2 Humble

**Excute the packages:**

First source the install where the colcon build has stored the files:

Source ROS2:

	source /opt/ros/humble/setup.bash

Source Repo:

	source install/setup.bash

Run:

  	ros2 launch ur_simulation_gazebo ur_sim_moveit.launch.py 

or
   
	ros2 launch ur_simulation_gazebo ur_sim_control.launch.py
	
To visualize the robot install this repository to you workspace and execute the following:

	ros2 launch ur_description view_ur.launch.py ur_type:=ur5e
	
 choices=["ur3", "ur3e", "ur5", "ur5e", "ur10", "ur10e", "ur16e", "ur20", "ur30"]
