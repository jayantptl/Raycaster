# Raycaster
A raycaster is a program that renders a 3D world based on a 2D map. It is a technique used in computer graphics to determine the visibility of objects in a 3D environment. It works by casting a "ray" from a point in the scene and checking for intersections with other objects.

The raycaster uses a digital differential analyzer (DDA) algorithm.
DDA is a fast algorithm typically used on square grids to find which squares a line hits. So we can also use it to find which squares of the map our ray hits, and stop the algorithm once a square that is a wall is hit.

![raycaster1](https://user-images.githubusercontent.com/96767549/232308720-a2355c24-3b05-4f77-9545-b7cc2fc50d62.png)
