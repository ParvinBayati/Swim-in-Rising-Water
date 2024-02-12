# Swim-in-Rising-Water

You are given an n x n integer matrix grid where each value grid[i][j] represents the elevation at that point (i, j).

The rain starts to fall. At time t, the depth of the water everywhere is t. You can swim from a square to another 4-directionally adjacent square if and only if the elevation of both squares individually are at most t. You can swim infinite distances in zero time. Of course, you must stay within the boundaries of the grid during your swim.

Return the least time until you can reach the bottom right square (n - 1, n - 1) if you start at the top left square (0, 0).

Constraints:

$n = \text{grid.length}$

$n = \text{grid[i].length}$

$1 \le n \le 50$

$0 \le \text{grid[i][j]} < n^2$

Each value grid[i][j] is unique.

![flowchart_swim_in_rising_water](https://github.com/ParvinBayati/Swim-in-Rising-Water/assets/91033182/1667bda5-d231-49e1-8d4d-fb4434b7fcfd)
Consider this example for the grid array

![grid](https://github.com/ParvinBayati/Swim-in-Rising-Water/assets/91033182/30fbc426-725d-47c5-aab4-a7359df92aab)


Possible paths for different times to reach the (n-1,n-1) square from square (0,0) are

![possible_path](https://github.com/ParvinBayati/Swim-in-Rising-Water/assets/91033182/1bca6986-3da1-4b39-b1b6-75dd869ccd4d)

Therefor, the minimum time to reach the final destination is $t=16$.
