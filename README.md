<img src="images/github-banner.jpg" 
    title="IDEC-ezWheel GitHub banner" 
    alt="IDEC-ezWheel GitHub banner"
    style="width: 100%; height: auto;">

# IDEC ez-Wheel Community

## Introduction

Welcome to the IDEC-ezWheel GitHub

Below, you will find an organized summary of all the resources, documentation and examples available on the IDEC-ezWheel GitHub.

## Table of contents

- [Introduction](#introduction)
- [Table of contents](#table-of-contents)
- [SWD® Drive \& Wheel Drive CANopen](#swd-drive--wheel-drive-canopen)
  - [Resources](#resources)
- [SWD® Starter Kit ROS](#swd-starter-kit-ros)
  - [Resources](#resources-1)
- [SWD® Starter Kit with ez-Way®](#swd-starter-kit-with-ez-way)
- [ez-Way® powered solutions](#ez-way-powered-solutions)
- [More IDEC Projects](#more-idec-projects)

## SWD® Drive & Wheel Drive CANopen

The SWD® Safety Wheel Drive provides a simple, versatile, and safety compliant technological brick for system integrators and AGV/AMR manufacturers. 

In addition to electric traction functions, SWD® motorizations natively embed safety, especially safe motion control and safety encoder.

### Resources

**Using a PLC**

| Name | Description |
| - | - |
| CANopen control (Quick Start SDO) | ... |
| Pseudo code | ... |
| CANopen CODESYS | ... |

**Using the IPC**

| Name | Description |
| - | - |
| [swd-services](https://github.com/IDEC-ezWheel/swd-services) | This repository contains an APIs for managing SWD® Drive |
| CANopen control (Quick Start - bash) | ... |

<!--
### Examples

* *no examples for now*
-->

## SWD® Starter Kit ROS

The SWD® Starter Kit ROS is designed to facilitate and accelerate the development of AGVs and AMRs using ez-Wheel’s exclusive SWD® Safety Wheel Drive technology and a SE2L safety laser scanner.

This version of the Starter Kit comes with ROS open-source middleware and the drivers for the control of the platform.

Product: https://www.ez-wheel.com/en/development-kit-for-agv-and-amr

### Resources

| Name | Description |
| - | - |
| [swd-starter-kit-docs](https://github.com/IDEC-ezWheel/swd-starter-kit-docs) | This repository guides you through your first steps with the ez-Way® Starter Kit and explain its architecture. |
| [swd_starter_kit_bringup](https://github.com/IDEC-ezWheel/swd_starter_kit_bringup) | This repository contains a sample ROS configuration for the SWD® Starter Kit. |
| [swd_starter_kit_description](https://github.com/IDEC-ezWheel/swd_starter_kit_description) | This repository contains the URDF file to use SWD® Starter kit with ROS 1. The URDF also contains the collision model and is suitable for Gazebo simulations. |
| [swd-starter-kit-config](https://github.com/IDEC-ezWheel/swd-starter-kit-config) | This repository contains a set of sample configuration files for the SWD® Starter Kit. |
| [swd_robot_manager](https://github.com/IDEC-ezWheel/swd_robot_manager) | This repository contains a set of helper nodes for the SWD® Starter Kit. |
| [swd_ros_controllers](https://github.com/IDEC-ezWheel/swd_ros_controllers) | This repository contains a ROS node that controls motors powered by ez-Wheel SWD® technology. |
| [swd_ros2_controllers](https://github.com/IDEC-ezWheel/swd_ros2_controllers) | This repository contains ROS2 nodes that controls motors powered by the ez-Wheel SWD® technology. |

<!--
### Examples

* *no examples for now*
-->

## SWD® Starter Kit with ez-Way®

The SWD® Starter Kit with ez-Way® is designed to facilitate and accelerate the development of AGVs and AMRs using ez-Wheel’s exclusive SWD® Safety Wheel Drive technology, a SE2L safety laser scanner and ez-Way® navigation software.

This version of the Starter Kit comes with the ez-Way® software featuring SLAM navigation for virtual line following.

Product: https://www.ez-wheel.com/en/development-kit-for-agv-and-amr

<!--
### Resources

* *no resources for now*

### Examples

* *no examples for now*
-->

## ez-Way® powered solutions

ez-Way® is a software for controlling and navigating mobile robots, ensuring smooth and efficient operations.

Installed on each machine, it guarantees mobile robot management, robot localization, navigation, and mission execution.

Product: https://www.ez-wheel.com/en/ez-way-software

**Documentation**

To access the following documentation, you must be connected to the access point of a robot with ez-Way® installed.

| Name | Description |
| - | - |
| [ez-Way® Documentation](http://10.42.0.1:8088/docs) | This page contains the ez-Way® documentation |
| [MQTT API Reference](http://10.42.0.1:8088/docs/mqtt_api_reference.html) | This page contains the "MQTT API Reference" section of the ez-Way® documentation |
| [Errors Reference](http://10.42.0.1:8088/docs/errors_reference.html) | This page contains the "Errors Reference" section of the ez-Way® documentation |

**Examples**

| Name | Description |
| - | - |
| [FC6A - Modbus TCP](https://github.com/ez-Support/ez-Way_Examples) | This repository contains an example showing how to control a PLC during a mission performed by ez-Way, using Modbus TCP communication |
| [FT2J - MQTT Communication](https://github.com/EYezWheel/ez-Way_and_FT2J_example) | This repository contains an example showing how an FT2J can be used to interact with ez-Way, using MQTT communication. |

## More IDEC Projects

[![IDEC](https://img.shields.io/badge/github-IDEC-a30000?logo=github)](https://github.com/idec-co)
