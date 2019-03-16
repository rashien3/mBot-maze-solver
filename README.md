# mBot-maze-solver
Introduction to Engineering Principles and Practices CG1111 Project for NUS, used an mBot to solve a maze based on external inputs such as sound, light, etc.

We designed our own infrared sensors and calibrated them, then in order to ensure that the mBot doesn't collide with the walls while it is solving the maze, we used PID (Proportional, Integral, Derivative) Controller available in the Arduino Library. 

The input for the PID came from the IR sensors that allowed the mBot to 'autocorrect' itself when it got too close with the walls.

At the end of the maze, it played a victory tune.

![Robot Side Picture](https://raw.githubusercontent.com/andyrobert3/mBot-maze-solver/master/Robot%20Side%20Pic.jpeg)
![Robot Front Picture](https://raw.githubusercontent.com/andyrobert3/mBot-maze-solver/master/Robot%20Front%20Pic.jpeg)
