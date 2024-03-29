# Robotics System Design Topics

## Framework

### ROS

What is ROS?
* Capabilities, e.g., [MoveIt](https://moveit.picknik.ai/main/index.html), [Nav2](https://navigation.ros.org/)
* Utilities, e.g., [tf](https://wiki.ros.org/tf), [Time](https://wiki.ros.org/roscpp/Overview/Time) and [Clock](https://wiki.ros.org/Clock), [ROS Command-line tools](https://wiki.ros.org/ROS/CommandLineTools)
* Simulation, e.g., [Gazebo](https://gazebosim.org/)
* Debug tools, e.g., [RViz](https://wiki.ros.org/rviz), [rosbag](https://wiki.ros.org/rosbag)
* Build, package management, deployment tools, e.g., [colcon](https://colcon.readthedocs.io/en/released/)/[catkin](https://wiki.ros.org/catkin), [rospack](https://wiki.ros.org/rospack), [bloom](http://bloom.readthedocs.org/)
* Documentation and communicty, e.g., [ROS Wiki](https://wiki.ros.org/Documentation), [ROS Answers](https://answers.ros.org/)

### Other Frameworks

* [YARP](https://www.yarp.it/)
* [Orocos](https://docs.orocos.org/)
* [MOOS-IvP](https://oceanai.mit.edu/moos-ivp/pmwiki/pmwiki.php)
* [ArduPilot](https://ardupilot.org/)

### Framework vs. No-Framework

Reasons for using a framework

* (Initial) Development speed
* Community and support

Reasons for not using a framework

* Performance
* Less dependencies/More control


## Zerocopy

### Considerations

* Serialization vs. Transport vs. Both
* Hardware dependency

### Examples

* [Cap'n Proto](https://capnproto.org/)
* [Zenoh](https://zenoh.io/)


## Build System

### Monorepo

Why?

* [Monorepo Explained](https://monorepo.tools/)
* [Building Self Driving Cars with Bazel](https://youtu.be/fjfFe98LTm8)

Why not?

* Team autonomy
* Migration & maintenance efforts


## Hardware-in-The-Loop Testing

* [CI for Embedded Systems](https://jamesmunns.com/blog/hardware-ci-overview/)
* [How to Build a Continuous Integration and Delivery Process for Embedded Software](https://medium.com/jumperiot/how-to-build-a-continuous-integration-and-delivery-flow-for-embedded-software-b0b5bf220a2)


## Deployment

* [The landscape of software deployment in robotics](https://web.archive.org/web/20230330175041/https://www.airbotics.io/blog/software-deployment-landscape)
