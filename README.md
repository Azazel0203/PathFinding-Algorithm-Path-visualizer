# PathFinding-Algorithm-Path-visualizer

A simple interactive pathfinding visualizer using JavaScript and the p5.js library.

![PathFinder Demo]([pathfinder-demo.gif](https://github.com/Azazel0203/PathFinding-Algorithm-Path-visualizer/blob/main/ezgif.com-gif-maker%20(1).gif))

## Introduction

This project implements a pathfinding algorithm visualizer using JavaScript and the p5.js library. The user can visualize how an algorithm (in this case, the A* algorithm) finds the shortest path between a start and end point on a grid. The grid can also include obstacles that the algorithm has to navigate around.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Click the "Start Path Visualize" button to start the visualization.
4. The algorithm will start finding the shortest path from the top-left corner (start) to the bottom-right corner (end) of the grid.
5. Observe how the open set, closed set, and the final path are displayed on the grid.

## Features

- Interactive visualization of the A* pathfinding algorithm.
- Click the "Start Path Visualize" button to begin the visualization.
- The grid includes randomly generated obstacles for added complexity.
- The algorithm will find the shortest path around the obstacles from start to end.

## Technologies Used

- HTML, CSS: Frontend structure and styling.
- JavaScript: Algorithm implementation and interactive behavior.
- p5.js: A JavaScript library for creative coding and visualization.

## About the Algorithm

The A* algorithm is a popular pathfinding algorithm that finds the shortest path between two points on a grid while considering the cost of each step and a heuristic estimate of the remaining distance. It intelligently searches through the possible paths and selects the one with the lowest cost.
