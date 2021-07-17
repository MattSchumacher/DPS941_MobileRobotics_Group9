# Reflections
## Matt's Reflection:
### Q1: What is mapping in autonomous robotics?
Mapping creates an environment that a robot will be able to interpret and use to navigate around its surroundings. The robot uses a variety of sensors, cameras and lasers to navigate. The goal of mapping is for a robot to autonomously navigate its environment. 
### Q2: How important is the map’s accuracy for the robot’s autonomous navigation task? 
The accuracy of the map is important because if the map is not accurate than there is the potential for the robot to become lost. 
### Q3: What are dynamic objects in autonomous robotics? Either explain or provide some examples.
Dynamic objects are objects that are moving. A few examples of these would be in a robot map, if you had blocks that could move horizontally or vertically that the robot could bump into. In a real-life practical sense, a self driving car would have to be aware of other cars which are dynamic objects because they are moving, but it would also be aware of signs such as a stop sign and traffic lights which would be considered static as they are not moving. 
### Q4: Should the dynamic objects be present when mapping an arena? Explain the reason for your answer.
In my opinion we should not map out dynamic objects because they are not truly part of the map.  The only situation I could see for potentially mapping out a dynamic object, is if that object will be in the same area, moving the same way, on a consistent basis. For example, if there is a map of a building and there is an elevator moving up and down, I would personally map that. The elevator is in the same spot, moving the same way, and it will always be there. If these conditions are not met, I would refrain from mapping a dynamic object. 
## Roman's Reflection:
### Q1: What is mapping in autonomous robotics?
Mapping is the process of understanding an environment for a robot. When robots navigate, they are continuously building a map of its surroundings. This allows for robots to be familiar with the setting they are in, which will enable them to safely navigate autonomously.
### Q2: How important is the map’s accuracy for the robot’s autonomous navigation task? 
The map’s accuracy is very important for a robot. If a robot is placed into an environment that it is unfamiliar with, it can cause it to make certain mistakes whilst navigating, which can be crucial to the success of the robot.
### Q3: What are dynamic objects in autonomous robotics? Either explain or provide some examples.
Dynamic objects in autonomous robotics refers to objects that are going to be in motion in an environment. An example would be another robot navigating within the same environment, or as we can think of a video game, where guards patrol within a certain area. These objects are not static, meaning that they are almost constantly in motion.
### Q4: Should the dynamic objects be present when mapping an arena? Explain the reason for your answer.
When mapping an arena, the dynamic objects do not need to be present. The reason as to why they do not need to be, is because if the robot has already mapped out the “static” parts of the environment. When it is navigating, it tries to keep itself centered and a certain distance away from the walls. So, when it is navigating to a specific coordinate within a map, if it detects a moving object approaching the robot, it will navigate away from it, but also navigate away from a wall.
