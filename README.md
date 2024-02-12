# Swim-in-Rising-Water

You are given an n x n integer matrix grid where each value grid[i][j] represents the elevation at that point (i, j).

The rain starts to fall. At time t, the depth of the water everywhere is t. You can swim from a square to another 4-directionally adjacent square if and only if the elevation of both squares individually are at most t. You can swim infinite distances in zero time. Of course, you must stay within the boundaries of the grid during your swim.

Return the least time until you can reach the bottom right square (n - 1, n - 1) if you start at the top left square (0, 0).

Constraints:

$n = grid.length$

$n = grid[i].length$

$1 <= n <= 50$

0 <= grid[i][j] < n^2

Each value grid[i][j] is unique.

![flowchart_swim_in_rising_water](https://github.com/ParvinBayati/Swim-in-Rising-Water/assets/91033182/60c22ff3-4740-4067-be9b-ff76ca6a2887)

Possible paths for different times to reach the end from square (0,0) for the example

![possible_path](https://github.com/ParvinBayati/Swim-in-Rising-Water/assets/91033182/5c0b54c6-fca0-4b76-9d19-e36db5e858a4)
