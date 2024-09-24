# Path Finding Visualizer
[![Netlify Status](https://api.netlify.com/api/v1/badges/f67f80f5-5b26-47b3-904f-9d8c203d5596/deploy-status)](https://app.netlify.com/sites/dijkstra-path-finder/deploys)

<img src="/src/img.jpg">

## Overview

This project is a Pathfinding Visualizer built using React. It helps visualize various pathfinding algorithms like Dijkstra's Algorithm, A Search*, Breadth-First Search (BFS), and Depth-First Search (DFS) on a grid. Users can interactively set start and end points, place obstacles, and watch how the algorithms explore the grid to find the shortest path.

## Features
Interactive Grid: Users can select the start and end points, place walls (obstacles), and adjust grid size.

Multiple Algorithms: Visualize popular pathfinding algorithms such as:

Dijkstra's Algorithm

A* Search

Breadth-First Search (BFS)

Depth-First Search (DFS)

Algorithm Visualization: Watch how different algorithms explore the grid to find the shortest path.

Real-Time Updates: The grid updates in real-time as the algorithms work their way through it.

Responsive Design: Works seamlessly on different devices and screen sizes.


## Installation

To run this project locally, follow these steps:

Clone the repository:

bash code
git clone https://github.com/yourusername/pathfinding-visualizer.git
cd pathfinding-visualizer
Install the dependencies:

bash code
npm install
Start the development server:

bash code
npm start
The app will be available at http://localhost:3000.

## Usage

Select Start and End Points: Click on the grid to set the starting and ending points for the algorithm.

Place Obstacles: Click on grid cells to place or remove walls that will act as obstacles for the algorithm.

Choose an Algorithm: Select an algorithm from the controls section and click "Start" to begin the visualization.

Watch the Visualization: Observe the algorithm as it explores the grid and finds the shortest path (if possible).

Reset Grid: Reset the grid to start a new pathfinding session.

Available Pathfinding Algorithms

Dijkstra's Algorithm: Guarantees the shortest path in a weighted grid.

A Search*: Optimized pathfinding using heuristics.


Breadth-First Search (BFS): Unweighted algorithm, guarantees the shortest path.

Depth-First Search (DFS): Unweighted algorithm, does not guarantee the shortest path.


## Example
When you open the app:

A grid is displayed where you can select the start and end points.

Place obstacles and choose an algorithm from the dropdown menu.

Watch the algorithm visualize its exploration and see how it finds the shortest path.

## Dependencies

React: Frontend framework for building the UI.

CSS or Styled Components: For styling the app and grid.

Algorithms: Custom implementation of pathfinding algorithms.

