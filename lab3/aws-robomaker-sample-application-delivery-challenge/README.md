# Reflections
## Matt's Reflection:
### Q1: What is autonomous navigation in mobile robotics?

### Q2: What parameters does the robot navigation algorithm consider when planning a path? 

### Q3: What is a cost map (in the context of autonomous navigation).

### Q4: What is inflation radius (in the context of autonomous navigation).

### Q5: Which navigation parameters did you tune using the document in the link below?

## Roman's Reflection:
### Q1: What is autonomous navigation in mobile robotics?
Autonomous navigation in mobile robotics could be defined as the robot having the ability to make it's own decision and act upon them, in this case being, navigating around a world to a specified coordinate location. Using several sensors, the robot percieves it's location in the world, scans the "dangers" around it self and acts accordingly.
### Q2: What parameters does the robot navigation algorithm consider when planning a path? 
When the robot navigation algorithm plans a path, it looks for inflation_radius and cost_scaling_factor as its primary parameters. The inflation radius parameter changes the inflation of the area from the bostacle. The higher the value the more distance that the robot keeps away from the object. The second parameter that the robot algorithm looks at is the cost_scaling_factor. This parameter tells the robot the cost of each object in the map. Meaning that it determines the cost map for the robot. The higher this value the cost is decreased, and vice versa.
### Q3: What is a cost map (in the context of autonomous navigation).
The cost map in autonomous navigation refers to a map that represents the "cost" or total difficulty of its actions in certain parts of
a map. For example, the cost of navigating in the center section of the default map is higher, due to unexpected moving objects.
### Q4: What is inflation radius (in the context of autonomous navigation).
The inflation radius in autonomous navigation increases the inflation area around an obstacle. The higher the inflation radius, the "scarier" the object is to robot. When the robot sees a higher inflation radius for objects, it accordingly changes the cost map for itself, to ensure a clear path with the least amount of issues.
### Q5: Which navigation parameters did you tune using the document in the link below?
The navigation parameters that we changed were sim_time to 5.00 in dwa_local_planner, as well as inflation_radius to 10.00 in costmap_common_params file. In the dwa_local_planner, we changed max_vel_x to 3.00, max_rot_vel to 6.00 and min_rot_vel to 3.00, acc_lim_x to 10, the acc_lim_theta to 10.
