# In Collab: Upload your code and a brief instruction on how to run it, together with a pdf document containing the data and plots requested below. Please upload a zip file containing all the files. The name of your files should begin with family name_first name (e.g. Bezo_Nicola_HW1.zip).

NB: Homework is individual!

Implement a non holonomic vehicle in Matlab with the following specs

max steering angle = pi/4

max speed = 5 m/s

workspace dimension 200m x 200m. The global frame is at (0,0)

create and represent a desired shape for your robot (triangle, rectangle, star,...) but NOT a triangle

The robot’s initial configuration is (100, 100, rand(θ))

Implement a homogeneous transformation creating a function in Matlab that translates the robot by a vector (x=#_letter of your name, y=#_letter of your family name) (e.g. A=1, B=2, C=3, etc.) and rotate by (pi/(5 + #_group). Plot the initial configuration and the final configuration in the workspace. (10 pt)

Go to goal. In this simulation pick a random goal point in the environment and drive the robot to it. The initial pose of the robot is as calculated in 1. The robot initial and final velocity have to be 0. Plot x and y position of the robot in the environment, and its velocities with respect to time. (30 pt)

Implement a cruise controller (i.e., PID) with vref = 3 m/s. Make the robot go through 3 random points in the environment and switch to next goal once the current goal has been visited. Assume that the velocity has the following dynamics (+1) =() +()−0.01() where u is the output from the PID and dt is the sampling time (e.g. dt=0.1) of your controller. Plot the velocity of the robot. (30pt)

follow a wall: draw a line in the workspace and make the robot follow the line at a constant distance (10m). Plot the relative distance between robot and line over time (30pt)

Extra points (10 pt) Pick either: A) Move to pose: robot starts in position (0,0,0) and needs to go to (130+ (#_letter of your name, 130+ #_letter of your family name, pi/(5 + #_group). Plot the initial pose, trajectory, and final pose, OR B) Follow a circle: draw a circle of radius r = 75m in the center of the workspace and make the robot follow it from any starting point of the workspace. Plot the position and velocities of the robots
