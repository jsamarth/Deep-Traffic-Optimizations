# Deep-Traffic-Optimizations

In this project, the task is to optimize the algorithm using Deep Reinforcement Learning to train an autonomous vehicle to weave its way through traffic, with the maximum speed possible. This code is for the Deep Traffic competition hosted by MIT at:
https://selfdrivingcars.mit.edu/deeptraffic/

The car has 5 options every time it has to take a decision:
* remain at the current speed
* accelerate
* decelerate
* turn left
* turn right

The car iteratively learns the action with the best reward, iteratively, by looking at the inputs, which are the number of sidelanes it can see, as well as the number of steps ahead it can see. I have varied these parameters, as well as the different hyperparameters of the net, and noticed different results. 

My results: by changing the hyperparameters, I have optimized the net to increase the average speed of the car to 70.31mph. Initially, we are given a net with average speed of less than 52mph.

# This is how the net parameters look:
![Image of the net parameters](https://raw.githubusercontent.com/jsamarth/Deep-Traffic-Optimizations/master/net_params.png)

# The traffic simulation, with random white cars, and the red autonomous car controlled by my algorithm:
![the traffic situation](https://raw.githubusercontent.com/jsamarth/Deep-Traffic-Optimizations/master/traffic.png)




