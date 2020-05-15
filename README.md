# mazeTest
These packages have been supplied to be used as example mazes for students in ECTE477.

###### practice_mazes:  
practice_mazes contains a selection of 9 different mazes, each with there own launch file, models and world files.
When launching either of the 9 mazes, the maze and a Turtlebot3 will be launched in Gazebo, ready for simulation.  
**roslaunch practice_mazes maze_0_world.launch**

###### maze_test_package:  
Similiar to previous, however this package only contains 1 maze. However this 1 maze also contains a visual beacon, that will
be used for image recognition experimentation.  
**roslaunch maze_test_package maze_test_world.launch**  

###### practice_mazes_beacon:  
Modified version of practice_mazes to include a visual beacon in each maze that can be identified bt the TurtleBot3.  
**roslaunch practice_mazes_beacon maze_0_beacon_world.launch** 
