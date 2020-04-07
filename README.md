# mazeTest
These packages have been supplied to be used as example mazes for students in ECTE477.

Practice Mazes:
Practice mazes contains a selection of 9 different mazes, each with there own launch file, models and world files.
When launching either of the 9 mazes, the maze and a Turtlebot3 will be launched in Gazebo, ready for simulation.
roslaunch practice_mazes maze_0_world.launch

Maze Test Package:
Similiar to previous, however this package only contains 1 maze. However this 1 maze also contains a visual beacon, that will
be used for image recognition experimentation.
roslaunch maze_test_package maze_test_world.launch
