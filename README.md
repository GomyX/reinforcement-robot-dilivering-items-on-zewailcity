# Q-Learning Robot for Object Delivery in Zewail City
## Overview 
This project aims to develop a robot capable of autonomously picking up objects from two different locations within Zewail City and delivering them to two specified destinations. The robot employs the Q-learning algorithm to learn optimal strategies for object delivery based on its experiences in the city. The city is represented as a graph, where nodes correspond to different places and edges with weights representing distances between them. By exploring the city and updating its Q-values, the robot learns to make informed decisions and efficiently navigate toward its goal.

## Features
1. Q-Learning Algorithm: The robot utilizes the Q-learning algorithm to learn optimal policies for object delivery. It learns the Q-values for each state it encounters, which represent the expected rewards for taking specific actions in those states.
2. Object Pickup and Delivery: The robot is programmed to pick up eight objects from two designated locations in Zewail City and deliver them to two specific destinations, with four objects for each destination.
3. City Exploration: The robot explores the city by traversing the graph representation of Zewail City. It learns about the distances between different places and updates its Q-values accordingly.
4. Reward System: The robot receives rewards based on its actions. It receives positive rewards for successfully delivering objects to its destinations and negative rewards for unsuccessful attempts. These rewards guide the learning process and help the robot optimize its decision-making.
5. Efficient Pathfinding: Through the Q-learning process, the robot discovers the most efficient paths for object delivery. It uses the learned Q-values to determine the best actions to take in each state, allowing it to navigate the city effectively.
