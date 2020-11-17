[![](https://github.com/ros-drivers/velodyne/workflows/Basic%20Build%20Workflow/badge.svg?branch=melodic-devel)](https://github.com/ros-drivers/velodyne/actions)

Overview
========

Velodyne<sup>1</sup> is a collection of ROS<sup>2</sup> packages supporting `Velodyne high
definition 3D LIDARs`<sup>3</sup>.

**Warning**:

  The master branch normally contains code being tested for the next
  ROS release.  It will not always work with every previous release.
  To check out the source for the most recent release, check out the
  tag `<version>` with the highest version number.

The current ``master`` branch works with ROS Kinetic and Melodic.
CI builds are currently run for Kinetic and Melodic.

# Windows

To build for ROS on Windows, start by installing ROS1 following the instructions at [Microsoft's ROS landing page](http://aka.ms/ros).

After installing, launching a ROS terminal, install the pcap dependency using the Microsoft vcpkg package manager:

``` batch
vcpkg install libpcap:x64-windows
```

Then build normally using `catkin_make`.


- <sup>1</sup>Velodyne: http://www.ros.org/wiki/velodyne
- <sup>2</sup>ROS: http://www.ros.org
- <sup>3</sup>`Velodyne high definition 3D LIDARs`: http://www.velodynelidar.com/lidar/lidar.aspx
