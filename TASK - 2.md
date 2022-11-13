
# Problem Statement 
Now that you have completed task 1 , we will get into spawning gazebo entities in this world and control it using cmd vel.
Use the internet , and explore gazebo to complete this task


The World :
![[Pasted image 20221113130340.png]]

The ebot:
![[Pasted image 20221113130631.png]]


# Problem Statement 1:
Your task is to spawn the ebot in the gazebo world and control it through teleop


1. Git clone the following rep in src directory and catkin make in workspace and source it

2. Execute the following statement
```sh
roslaunch ebot_description ebot_gazebo.launch
```

3. The gazebo world is the racetrack world.
4. You need to spawn on the start line on the race track , not 0 , 0 , 0 coordinates 
4. Add a gazebo plugin (skidsteer drive) to control the ebot.
5. Control your bot using cmd vel commands 

Hints:
1. Use [Teleop](http://wiki.ros.org/teleop_twist_keyboard):
2. Refrence [Turtlbot3](https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/)


---


