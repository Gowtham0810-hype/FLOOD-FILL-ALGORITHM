# FLOOD-FILL-ALGORITHM

Flood-fill algorithm is a kind of algorithm largely used in computer graphics and image 
processing to determine the connected region within a multi-dimensional array (such as a 
two-dimensional grid or bitmap).

At its core, the flood fill algorithm starts at a specific point in the array and progressively 
visits its neighbouring cells, comparing their characteristics to the starting point. It 
iteratively examines adjacent cells and extends the region until it encounters boundaries or 
conditions that indicate the region's limit

Here we are using flood-fill algorithm to map a maze and find the shortest distance between 
initial and final point within the maze hence solving the maze.
Recursive function implementation of flood-fill exists. However, it's important to implement 
the algorithm efficiently, especially for larger arrays, as the recursive version may cause 
stack overflows due to excessive function calls. Therefore, queue implementation of the 
algorithm is done in this project.
