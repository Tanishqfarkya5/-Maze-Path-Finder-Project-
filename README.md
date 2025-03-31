# **Maze Path Finder - README**

## **Project Overview**
The **Maze Path Finder** is a Python-based project that uses **Q-Learning**, a reinforcement learning approach, to solve randomly generated mazes. The robot learns to navigate from the **start point** to the **goal** through trial-and-error, optimizing its path using Q-values.

## **Features**
- **Dynamic Maze Generation**: Randomized mazes with customizable dimensions and wall density, ensuring solvability.
- **Reinforcement Learning**: Implements **Q-Learning** with configurable parameters like exploration rate (**epsilon**), discount factor (**gamma**), and learning rate (**alpha**).
- **Robot Navigation**: Tracks visited states, avoids loops, and penalizes walls to ensure optimal navigation.
- **User-Friendly GUI**: Built with **Tkinter** for easy maze configuration and real-time training visualization.
- **Progress Monitoring**: Displays training updates and allows visualization of the robot's learned paths.

## **Setup and Requirements**
### **Prerequisites**:
- **Python 3.x**
- **NumPy**
- **Tkinter** (pre-installed with Python)
- **JSON**
- **Queue**
- **OpenCV** (optional for enhanced visualization)
