# Human-Robot-Collaboration
- This project was a part of my Masters in AI focussing on Robotics Systems and Path Planning </br>
- The project deals with Human Robot Collaboration and its aim was to complete a given task of blocksworld domain.
- The robot considered was Maria Robot with two UR5 Arms.The task was to connect the blocks together in the environment. Both arms were used to complete the task.</br>
- Softwares and Tools Used :
  - ROS </br>
  - MoveIt- for path planning and manipulation </br>
  - Gazebo- for simulation  </br>
- 3 nodes were created - 
  - Perception - to get the percept of the environment. 
    - It captures and publishes the coordinates of the block to rostopic (red_coordinates, blue_coordinates, yellow_coordinates)</br>
  - Decision - to decide the arm movement. 
    - It subscribes to the rostopic (red_coordinates, blue_coordinates, yellow_coordinates) to fetch the coordinates of the blocks in order to decide the move</br>
  - Action - to move the robot arm. 
    - According to the moves , this node executes the action </br>
- Below are the videos of the scenario implementation :
  - 1. https://youtu.be/tCzIfFm6vDE</br>
  - 2. https://youtu.be/u2bcYT2Wfvk</br>
##
