Sudoku AI 

## Algorithm

**Constraint Propagation**

Sudoku has local constraints to each square. These constraints help you narrow the possibilities for the answer, therefore extracting the maximum information out of these constraints will  get closer to the solution.  
Repeatedly apply simple constraints to iteratively narrow the search space of possible solutions. 

**Search**

In the process of problem solving, there are two or more possibilities are available.  Branch out possibilities one of them will lead us to a position in which three or more possibilities are available. Then, branch out again. At the end, a whole tree of possibilities and find ways to traverse the tree until we find our solution. .
