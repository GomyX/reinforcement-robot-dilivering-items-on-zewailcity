# Q-Learning Robot for Object Delivery in Zewail City
## Overview 
This project aims to develop a robot capable of autonomously picking up objects from two different locations within Zewail City and delivering them to two specified destinations. The robot employs the Q-learning algorithm to learn optimal strategies for object delivery based on its experiences in the city. The city is represented as a graph, where nodes correspond to different places and edges with weights representing distances between them. By exploring the city and updating its Q-values, the robot learns to make informed decisions and efficiently navigate toward its goal.

## Features
1. Q-Learning Algorithm: The robot utilizes the Q-learning algorithm to learn optimal policies for object delivery. It learns the Q-values for each state it encounters, which represent the expected rewards for taking specific actions in those states.
2. Object Pickup and Delivery: The robot is programmed to pick up eight objects from two designated locations in Zewail City and deliver them to two specific destinations, with four objects for each destination.
3. City Exploration: The robot explores the city by traversing the graph representation of Zewail City. It learns about the distances between different places and updates its Q-values accordingly.
4. Reward System: The robot receives rewards based on its actions. It receives positive rewards for successfully delivering objects to its destinations and negative rewards for unsuccessful attempts. These rewards guide the learning process and help the robot optimize its decision-making.
5. Efficient Pathfinding: Through the Q-learning process, the robot discovers the most efficient paths for object delivery. It uses the learned Q-values to determine the best actions to take in each state, allowing it to navigate the city effectively.

## Getting Started
1. Install the notebook
2. Set up the graph representation of Zewail City, defining nodes to represent different places and edges with weights to represent distances between them.
3. Implement the Q-learning algorithm, including the exploration-exploitation trade-off and Q-value updates based on rewards received.
4. Define the object pickup and delivery mechanism, ensuring that the robot can accurately pick up objects from the specified locations and deliver them to the assigned destinations.
5. Run the learning process, allowing the robot to explore the city, update its Q-values, and improve its decision-making.
6. Once the learning process is complete, run the robot using the learned Q-values to guide its actions and observe its performance in delivering objects efficiently.

## results 
the robot is making just two more steps over the optimum number of steps for the robot to be optimum

## Future Enhancements
* Here are some potential improvements and extensions for this project:

1. Dynamic City: Allow the robot to adapt to changes in the city environment, such as new obstacles, modified distances, or additional destinations.
2. Multi-Robot Collaboration: Explore the possibility of multiple robots working collaboratively to improve the efficiency and speed of object delivery.
3. Real-time Updates: Implement a mechanism to update the Q-values in real-time based on the robot's experiences during object delivery, enabling continuous learning and adaptation.
4. Environmental Constraints: Incorporate constraints related to energy consumption, traffic congestion, or time limitations to optimize the robot's decision-making process.
5. Integration with External Systems: Integrate the robot's decision-making process with external systems, such as traffic monitoring or weather forecasts, to make more informed delivery decisions.
