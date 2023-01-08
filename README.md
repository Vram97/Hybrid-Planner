# Motion Planning in Dynamic and Hostile Environments
![alt text](https://production-media.paperswithcode.com/tasks/Screen_Shot_2019-05-28_at_9.57.56_PM_bUL5S86.png)
# Contents
1. Introduction
2. Setup
3. Run
4. Output

## Introduction
The folloiwing project was carried out as part of the RBE550 Motion Planning course. The aim of the project is to devise a motion planning algorithm for a robot to autonomously navigate to and from a goal location while avoiding both hostile dynamic agents as well as static obstacles. The motion of the robot, from start to goal and then back to the start is planned using a combination of a sampling based algorithm and an algorithm that works well in dynamic environments. The robot in this problem has to navigate to a goal position and then re-navigate back to its start location, in the presence of both static as well as non-deterministic dynamic agents. Therefore, a hybrid algorithm that fuses Rapidly Exploring Random Tree (RRT) to plan the initial path and an Artificial Potential Field (APF) algorithm to avoid dynamic obstacles, was used to solve the problem. Please go through the [Project Report](https://github.com/Vram97/Hybrid-Planner/blob/main/Final_Report.pdf) for more details.

## Setup
The following libraries need to be installed to run the code:
- numpy 
- matplotlib   
- collections
- scipy
- math
- random
- impedance_modeles 
- time
- progress
- tasks
- matplotlib
- math

## Run
Store all the files within the same folder and run the [gradient_interactive.py](https://github.com/Vram97/Hybrid-Planner/blob/main/gradient_interactive.py) file.

## Output
![alt text](https://github.com/Vram97/Hybrid-Planner/blob/main/apf.png)
