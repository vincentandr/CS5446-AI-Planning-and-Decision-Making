Homework 1 utilizes STRIPS to solve deterministic planning problems. [Gym Grid Driving](https://github.com/cs4246/gym-grid-driving) is used as the problem environment. 

## Task A - Parking Lot problem
The task requires the agent to drive the car from the start position to the goal position. Some cars occupy the parking spaces and serve as obstacles, and the agent must not crash into them while trying to get to the goal.
The agent has the action space of: UP, DOWN, FORWARD.

## Task B - Crossing the Road problem
The problem environment is similar to task A, with the modification of the obstacle cars can move within a certain speed range. All cars have the same speed range on the same lane, but differ across lanes.
The agent now has the action space of: UP, DOWN, FORWARD[-1], FORWARD[-2], FORWARD[-3].

