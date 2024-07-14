# Manipulate-with-turtlesim-package-in-ROS-noetic
in this project i will show you how to Manipulate with turtlesim package in ROS noetic in the easiest way possible 


introduction:

Robot Operating System (ROS) is a flexible framework for writing robot software. ROS Noetic is the latest long-term support (LTS) release targeting Ubuntu 20.04 (Focal Fossa). The turtlesim package is a simple simulator that helps new users learn ROS basics. 

-Step 1: Ros1 noetic installations

you need to install Ros1 noetic you can easely click in this link and will open another repository for you that will show you how to install thr Ros1 noetic very easily 

https://github.com/Sultan-Alghamdi94/Install-ros-on-ubuntu20.04

![Screenshot (680)](https://github.com/user-attachments/assets/a37f676f-afb9-4285-bb52-f19d9e51bba5)


-Step 2: Running the Turtlesim Package

after you finsh installing the Ros1 now all you need is to :

1-Open a terminal and start the ROS master node:

roscore

This starts the ROS master, which manages communication between ROS nodes. Leave this terminal open and running.

2-Run the Turtlesim Node:

Open a new terminal window. Source the ROS environment:

source /opt/ros/noetic/setup.bash

3-Run the turtlesim_node to start the turtle simulation:

rosrun turtlesim turtlesim_node

A window should open displaying a turtle in a blue background.

![Screenshot (681)](https://github.com/user-attachments/assets/f56fc38d-1650-4053-b62b-53458d2b23b8)


4-Control the Turtle:

Open yet another terminal window. Source the ROS environment again:

source /opt/ros/noetic/setup.bash

5-Run the turtle_teleop_key node:

this will help you to control the turtle with your keyboard:

rosrun turtlesim turtle_teleop_key

now you can Use the arrow keys on your keyboard to control the turtle's movement.

![Screenshot (682)](https://github.com/user-attachments/assets/571f9480-de9e-4075-a491-e5644f426d12)

6-The finel result:

![Screenshot (679)](https://github.com/user-attachments/assets/a829bc77-febb-48ff-9ff1-070cfca003db)
![Screenshot (685)](https://github.com/user-attachments/assets/481d5f54-2d6e-41c9-ad8c-2d3b9460c2ee)


Summary
You should now have:

Terminal 1: Running roscore.
Terminal 2: Running rosrun turtlesim turtlesim_node.
Terminal 3: Running rosrun turtlesim turtle_teleop_key.
With these steps, you have successfully installed ROS Noetic, ran the turtlesim simulator, and controlled the turtle using your keyboard. This setup provides a foundational understanding of how to work with ROS and its nodes.
