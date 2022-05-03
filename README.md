**Rat in a Maze**

Rat in a Maze is a popular problem of coding interviews based on the Backtracking algorithm. In this article, I will be Illustrating the Approach to Solve Rat in a Maze
Problem using Backtracking in C++.

**What is Backtracking?**

A backtracking algorithm attempts to build a solution to a computational problem incrementally, one small piece at a time. Whenever the algorithm needs to decide between 
several alternatives to the next component of the solution, it recursively evaluates each alternative and then chooses the best one. In simple words, backtracking is a 
recursive technique, which attempts to solve problems by assuming parts of the solution. After assuming the first part of the solution, we move on to assume the second 
part of the solution and so on. If we are lucky, all of the assumptions we made form a complete solution and the problem is solved. 
If the chosen path does not return a solution, then we go back. This means that we undo the last part of the solution we assumed and try another. This continues until we
find a solution, or try all the possibilities and see that a solution does not exist.

**Problem Statement**

Given an N*N Matrix, a Rat is initially at cell [0][0]. Find and Print the path Rat needs to follow to get out of the Maze. The Matrix consists of 0's and 1's 
representing Walls and Empty cells respectively. The Rat is free to move in any of the four directions (left, right, up, down). However, the Rat cannot pass through 
blocked Walls. Note - The Destination is assumed to be the Cell [N-1][N-1].


![image](https://user-images.githubusercontent.com/83498405/166465371-2fef9d5d-4f46-45d5-b127-ef456971c432.png)


**Code**

Attached in Main File In Repository. 

**INPUT**

5

1 0 1 0 1

1 1 1 1 1

0 1 0 1 0

1 0 0 1 1

1 1 1 0 1

**OUTPUT**

1 0 0 0 0

1 1 1 1 0

0 0 0 1 0

0 0 0 1 1

0 0 0 0 1
