# Firefighter Robot - AI for Navigating a Burning Ship

Description:

This project simulates the operation of multiple firefighter robots (bots) within a burning ship. The goal of the bots is to navigate the ship, locate a hidden button, and press it to stop the fire. The ship is represented as a grid, and the bots use various AI algorithms to find the button while avoiding fire and closed doors.

Features:

Four different bots with distinct navigation strategies.
Dynamic fire propagation based on flammability.
Adaptive heuristics for path planning.
Randomly generated ship layout for each run.
Provides success/fail outcomes for bot missions.

Bots:

Bot 1 (BFS): Uses Breadth-First Search for path planning.
Bot 2 (Modified BFS): Also uses BFS, considering fire locations.
Bot 3 (Modified BFS with Heuristic): Adds an adaptive heuristic to BFS.
Bot 4 (A with Adaptive Heuristic):* Utilizes the A* algorithm with an adaptive heuristic that considers nearby fire.

This project offers an engaging simulation of real-world scenarios where AI-driven robots must make intelligent decisions to navigate a dynamic environment with limited information.
