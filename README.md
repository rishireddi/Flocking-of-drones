# Flocking-of-drones
Polygon formation using multiple drones using mavros

# Software Development Tutorials
- Installing Ardupilot and Mavproxy [20.04]
  -> https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/Installing_Ardupilot_20_04.md
- Installing QGC
  -> https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/installing_qgc.md
- Installing gazebo and ardupilot plugin
  -> https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/installing_gazebo_arduplugin.md
- Installing ROS and Mavros [20.04]
  -> https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/installing_ros_20_04.md
- Controlling drones with Ardupilot + Mavros
  -> https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/multi_mavros_drones.md

To see the pattern formation run the below command:
- Run the gazebo sim
   
    roslaunch iq_sim runway.launch
- Run the ardupilot instance
  
    ./multi-ardupilot.sh
- Run the mavros instances
  
    roslaunch iq_sim multi-apm.launch
- Run the guidance program
  
    roslaunch iq_gnc mavros_flocking.launch




