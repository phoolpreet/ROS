## ROS 2

### Install

https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html

source /opt/ros/jazzy/setup.bash

---

### Install colcon

sudo apt install 

python3-colcon-common-extensions

source /usr/share/colcon_argcomplete/hook/colcon-argcomplete.bash

---

### Creatw Workspace

mkdir ros2_ws

cd ros2_ws

mkdir src

colcon build

source ~/projects/ROS/ros2_ws/install/setup.bash

---


ros2 pkg create mmy_robot_controller --build-type ament_python --dependencies rclpy