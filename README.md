# Robotics-Software-Engineer

![](https://github.com/nikhilamalajerrin/Localization-of-mobile-robot/blob/master/1.JPG)
![](https://github.com/nikhilamalajerrin/Localization-of-mobile-robot/blob/master/2.JPG)
![](https://github.com/nikhilamalajerrin/Localization-of-mobile-robot/blob/master/picture3.JPG)

## Build Instructions
1. Make sure you have the following installed:
   - [ROS](http://wiki.ros.org/ROS/Installation)
   - [Cmake](https://cmake.org/)
   - [Git](https://git-scm.com/)
2. Create two ROS packages inside your catkin_ws/src: the drive_bot and the ball_chaser. Here are the steps to design the robot, house it inside your world, and program it to      chase white-colored balls
3. Create a my_robot ROS package to hold your robot, the white ball, and the world
4. Design a differential drive robot with the Unified Robot Description Format
5. House your robot inside the world you built in the Build My World project
6. The world.launch file should launch your world with the white-colored ball and your robot: 
`Create a ball_chaser ROS package to hold your C++ nodes.
 Write a drive_botC++ node that will provide a ball_chaser/command_robot service to drive the robot by controlling its linear x and angular z velocities. 
  Write a process_image C++ node that reads your robot’s camera image, analyzes it to determine the presence and position of a white ball. If a white ball exists in the image,   your node should request a service via a client to drive the robot towards it.
  The ball_chaser.launch should run both the drive_bot and the process_image nodes'
7. make and run the launch file
8. The directory structure and contain all the files listed here`

## Structure
```
.Project3                          # Where am I
 ├── src
 │  ├── my_robot                       # my_robot package                   
 │  ├── ball chaser                     # launch folder for launch files   
 │  ├── main
 │  ├── odom_to_trajectory
 │  ├── pgm_map_creator                    # meshes folder for sensors
 │  
 │   
```
