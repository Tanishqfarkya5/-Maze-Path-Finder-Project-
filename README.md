Maze Path Finder - README
Project Overview
The Maze Path Finder is a Python-based project that employs Q-Learning, a reinforcement learning technique, to navigate through randomly generated mazes. The project simulates a robot that learns to find the optimal path from the starting point to the goal through trial-and-error, improving its decisions using Q-values.

Features
Random Maze Generation:

Mazes are dynamically generated with adjustable dimensions and wall density.

A guaranteed path from start to goal is carved for solvability.

Reinforcement Learning:

Utilizes Q-Learning with parameters like epsilon for exploration, gamma for discounting long-term rewards, and alpha as the learning rate.

Features Boltzmann exploration for improved action selection.

Robot Navigation:

The robot attempts to learn the best path to the goal, with penalties for hitting walls or revisiting states.

Tracks visited states and adapts to changing maze layouts.

Visualization:

A user-friendly GUI built with Tkinter allows real-time configuration and monitoring.

Displays the maze, the robot's progress, and paths it has learned.

Configurable Parameters:

Maze dimensions, wall probabilities, and training episodes can be adjusted through the GUI for flexibility.

How It Works
Maze Generation:

Randomly generates a maze grid with walls and paths based on the specified probability for wall density.

Guarantees a valid path from the start to the goal to avoid unsolvable mazes.

Q-Learning:

The robot explores the maze, learns from rewards/penalties, and builds a Q-Table to optimize its navigation strategy.

Rewards include moving closer to the goal or reaching it, while penalties apply for hitting walls, looping, or moving away from the goal.

Real-Time Visualization:

The application visualizes the maze and the robot's progress during training.

Training progress is displayed, providing insights into the robot's learning process.

Setup and Requirements
Prerequisites:
Ensure you have the following libraries installed:

Python 3.x

NumPy

Tkinter (usually included in Python installations)

JSON

Queue

OpenCV (if planning to expand visualization)

Installation:
Clone the repository to your local machine:

bash
git clone <repository-url>
Install required libraries using pip:

bash
pip install numpy opencv-python
Run the application:

bash
python maze_path_finder.py
Usage
Start the Application: Launch the GUI by running the script.

Configure the Maze: Adjust the maze's width, height, and wall probability through the GUI.

Train the Robot: Begin Q-Learning to train the robot to navigate the maze.

Visualize the Path: Observe the robot's exploration, learning, and eventual optimal pathfinding.

Future Improvements
Expand support for larger mazes and 3D mazes.

Enhance GUI for more interactive user experience.

Implement additional pathfinding algorithms like A* for comparison.

Optimize Q-Learning for faster convergence and better scalability.

Contributions
Feel free to contribute by submitting pull requests or raising issues for bugs and enhancements.
