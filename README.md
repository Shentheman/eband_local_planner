eband_local_planner
===================

The [eband_local_planner](http://wiki.ros.org/eband_local_planner) is
a [ROS](http://wiki.ros.org) package, implementing a plugin to the
[base_local_planner](http://wiki.ros.org/base_local_planner) for the
[move_base](http://wiki.ros.org/move_base) 2D navigation system.

It implements the Elastic Band method on the SE2 manifold.

# Installation
* You have to install the release version of the original [`utexas-bwi/eband_local_planner`](https://github.com/utexas-bwi/eband_local_planner) first by `$ sudo apt-get install ros-indigo-eband-local-planner` before being able to build this package. Otherwise, an error about the missing file [`eband_local_planner/EBandPlannerConfig.h`](https://github.com/Shentheman/eband_local_planner/blob/kinetic/include/eband_local_planner/eband_visualization.h#L46) will raise. That should be a bug of [`ros-autom/eband_local_planner`](https://github.com/ros-autom/eband_local_planner).
