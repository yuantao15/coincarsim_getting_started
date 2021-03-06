# Overview Source Dependencies

* Note: all source dependencies are automatically downloaded using the `*.rosinstall` file (see [installation step 2](README.md#2-download-the-workspace-config))

#### External Dependencies
* [automated_driving_msgs](https://github.com/fzi-forschungszentrum-informatik/automated_driving_msgs): messages used by the framework
* [lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2): map framework for automated driving
* [mrt_cmake_modules](https://github.com/KIT-MRT/mrt_cmake_modules): cmake helper
* [rosinterface_handler](https://github.com/KIT-MRT/rosinterface_handler): ROS interface handling


#### Parts of this Framework

* located under `https://github.com/coincar-sim/<repo-name>`


* general functionality:
  * simulation_initialization_ros_tool: settings and launchfiles
  * simulation_management_ros_tool: core functionality (localization, time and initialization management)


* sample vehicle:
  * sim_sample_perception_ros_tool
  * sim_sample_prediction_ros_tool
  * sim_sample_planning_ros_tool
  * sim_sample_actuator_ros_tool
  * sim_sample_communication_ros_tool


* visualization:
  * desired_motion_rviz_plugin_ros
  * lanelet_rviz_plugin_ros
  * motion_state_rviz_plugin_ros
  * object_state_array_rviz_plugin_ros


* utilities:
  * lanelet2_interface_ros
  * simulation_only_msgs: additional messages
  * util_automated_driving_msgs
  * util_eigen_geometry
  * util_geometry_msgs
  * util_rviz
  * util_simulation_only_msgs


* see the readme of the respective package for details
