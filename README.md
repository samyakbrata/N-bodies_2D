# N-bodies_2D
The project is a simplistic and small scale simulation of n-bodies with flexible frames of reference and certain other features in a purely newtonian flatland.

The motions are calculated by vector adding all the pairwise forces at play for a particular body, and repeating the same process for all bodies present. The model of collisons have been inplemented by making mass of one of the colliding bodies zero, effectively making it inconsequential, and increasing the mass of the remaining body. The different frames of references are implemented by basically changing x and y limits of the grapth according to need, for example from the position coordinate of CoM. The trails behind the bodies represent their previous positions and length of the trails upto a specific time in past, hence their lengths are roughly proportional to their present velocities.

## Features: 
  1. Vaious frames of reference:
       1. Center of Mass
       2. Any Body of choice
       3. Absolute
  2. Trails from previous position data
  3. Energy Analysis
  4. Pairwise motion Analysis

## Things needs to be worked upon:
  1. Inefficiency with large number of bodies
  2.  Implementation of Euler Algorithm
  3.  Extending to 3rd Dimension


## Here are some of the results :)

1. For 4 bodies follwing inverse square law:
![alt text](https://github.com/samyakbrata/N-bodies_2D/blob/main/media/git.gif)

2. Motion of one body with respect to another in the same simulation (non-inertial) :
![alt text](https://github.com/samyakbrata/N-bodies_2D/blob/main/media/gitt.gif)

3. Motion of all the bodies with respect to one (non-inertial):
   ![alt text](https://github.com/samyakbrata/N-bodies_2D/blob/main/media/gittt.gif)
