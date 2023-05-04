# Perfect-Maze-Generator
A perfect maze generator using a depth-first search algorithm

The Perfect Maze Generator is a simple project that generates perfect mazes of various sizes using a depth-first search algorithm. A perfect maze is a maze with no loops or inaccessible areas and exactly one path between any two points.

# Features
Initialize the maze with blank characters and walls
Create a perfect maze using a depth-first search algorithm
Print the maze

# Data Structures
Class: Maze for managing the maze and related operations
Two-dimensional char array: M for representing the maze grid
Integer: size for storing the size of the maze

#Usage
Compile and run the project
Follow the prompts to generate and interact with the perfect maze

# Task Breakdown
Implement the Maze class and its methods, keeping in mind the following requirements:
a. The method Initialize populates matrix M with blank characters and walls (e.g. ‘-’ and ‘|’). The size of the matrix may be greater than n to accommodate the “walls” and any other boundaries.
b. The method Create invokes DepthFirstSearch to build the perfect maze. As the depth-first search is performed, if two or more adjacent positions are unvisited, then one direction is randomly chosen.
Implement a main program to test the methods of Maze for n=0, 1, 2, 5, 10, 20.

License
This project is open source and available under the MIT License.
