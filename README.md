# AI
Artificial Intelligence algorithms

**Eight Puzzle Problem**

The task is to move the blank up, down, left or right in order to change the board position from start state to goal state.
- This problem can be solved by breadth first search (bfs), depth first search (dfs) which are exhaustive search but guarantees to find solution if it exist.
- Since dfs will not guarantee optimal solution and might lead to endless search against one branch and bfs require a lot of memory consumption but it guarantees optimal solution. So we can combine advantage of both in next algorithm called iterative deepening search (ids).
- Next solution is use heuristic function to find most promising node to explore. Hill Climbing, Best first and A star are hueristic search algorithms.
- Heuristic function used is H(X) = Number of tiles at correct position.
- Steps to run EightPuzzle.py 
  - Change start and goal state in the script, if you want.
  - Run `python EightPuzzle.py [bfs|dfs|ids|hill_climbing|best_first|a_star]`.
