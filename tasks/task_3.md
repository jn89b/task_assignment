# ROS2 and Unity
Your task will be to integrate your pathplanning algorithms (A* and Dijksras) into a ROS2 node and have it communicate with Unity.

## Deliverables for ROS2 Node
Your ROS2 node should be able to do the following:
- Take in a start and goal position in Unity coordinates
- Publish a path to Unity
- Have the Unity environment follow the path

## Deliverables for Unity
Your Unity environment should be able to do the following:
- Have the user input a start and goal position and send it to ROS2
- From your path planning node generate a colored path in Unity


## Initial Setup/Getting Started
- Run the install_unityhub.sh to download UnityHub and vscode
- Run the docker container from https://github.com/jn89b/project_sandbox and follow the instructions on the readme
- Before getting started on your task follow this tutorial to understand how to communicate between ROS2 and Unity:
    - https://github.com/Unity-Technologies/Unity-Robotics-Hub/blob/main/tutorials/ros_unity_integration/publisher.md
    - https://github.com/Unity-Technologies/Unity-Robotics-Hub/blob/main/tutorials/ros_unity_integration/subscriber.md
- Make sure to follow the ros2 tutorial and not the ros1 tutorial
