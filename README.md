# Virtual-Self-Driving-Car-TD3-

### This repo contains TD3 algorithm implementation on MUJOCO environment. 

### The TD3 algorithm is also implemented for a virtual self driving car on a kivy environment. 
### [The link to the video](https://youtu.be/NjjyNLct40A)

### The car/agent uses the vision/image of surrounding the region of car on the map and the orientation with respect to its axis to move in the envirnoment. 

## Another implementation of this project, without using CNN.

### In this implementation, the car was provided with 3 sensors which can be thought of as the headlights of the car. These 3 sensors collect data (pixel values) from the envirnoment & feed it to the network. The network outputs the action to be taken by the agent. 
### [The link to the video](https://www.youtube.com/watch?v=-gIItfj7f3o)

## Note : 
### There can be substantial amount of improvements which can be added to the code to the make the movement of the car more precise and accurate. As of now, the input to the TD3 network is a patch of map/image surrounding the car. I aim to add the orientation of the car with respect to the goal state as-well in the hope of making it more precise, along with changes in envirnoment variables. 
