# Bash Scripts
Bash scripts are a huge part of this project. They are not needed, but make your life way easier. Please use them.  
<br>
Cheers,  
Sam

<br>
### Install Steps:  
- Navigate to home directory using command `cd ~`  
- Create a new directory "bin" using `mkdir bin`  
- Navigate to directory using `cd bin` and place bash scripts inside  
- Make scripts executable by running command `chmod +x [name of script]`  
<br><br>
### Usage:  
From any directory... 
```
[name of command]
Ex:
start-image-read
```
## start-image-read
This will run the object detection model through the Turtlebot camera, and publish a stream of compressed images containing the predicted bounding boxes. Process can be exited using `stop-image-read`
#### Run these first:
* roscore
* bringup (pi)
* camera (pi)
* run-rviz *(recommended)*
<br><br>
## run-rviz
Runs relevant commands to load the turtlebot in Rviz. Make sure to have [PC] `roscore` and [Pi] `./bringup.sh` running in separate terminals first.
<br>
## run-teleop
Enables teleoperation for the turlebot using arrow keys on laptop. Previous steps apply.
<br>
## gits
Runs command `git status`, but with less characters needed. A simple but effective script for lazy programmers.
