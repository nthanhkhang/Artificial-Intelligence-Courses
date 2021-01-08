# Artificial_Intelligence_Courses
Using Backtracking and Forward Tracking algorithms in problems:

## I.	Algothrims 8 Queens Problems:
  
### 1.What is?
  
The N Queen is the problem of placing 8 chess queens on an 8×8 chessboard so that no two queens attack each other. For example, following is a solution for 4 Queen problem.
		 
### 2.	Backtracking:

To solve this problem, we will make use of the Backtracking algorithm. The backtracking algorithm, in general checks all possible configurations and test whether the required result is obtained or not. For thr given problem, we will explore all possible positions the queens can be relatively placed at. The solution will be correct when the number of placed queens = 8.

Input Format - the number 8, which does not need to be read, but we will take an input number for the sake of generalization of the algorithm to an NxN chessboard

Output Format - all matrices that constitute the possible solutions will contain the numbers 0(for empty cell) and 1(for a cell where queen is placed). Hence, the output is a set of binary matrices.

### 3.	Demo:
[8_queen_Backtracking](https://github.com/nthanhkhang/Artificial-Intelligence-Backtracking/blob/main/8_queen_Backtracking.ipynb)

## II.	Permutation Algothrims:

### 1.What is Permutation Algothrims?

A permutation, also called an “arrangement number” or “order,” is a rearrangement of the elements of an ordered list S into a one-to-one correspondence with S itself. A string of length n has n! permutation.

### 2.BackTracking Algothrims

In the implementation of the state transfer, we can use either BFS or DFS on the implicit vertices. DFS is preferred because theoretically, it took O(log n!) space used by the stack, while if use BFS, the number of vertices saved in the queue can be close to n!. With recursive DFS, we can start from node [], and traverse to [1,2], then [1,2,3]. Then we backtrack to [1,2], backtrack to [1], and go to [1, 3], to [1, 3, 2]. To clear the relation between backtracking and DFS, we can say backtracking is a complete search technique and DFS is an ideal way to implement it. 

We can generalize Permutation, Permutations refer to the permutation of n things taken kat a time without repetition, the math formula is A_{n}^{k} = n *(n-1)*(n-2)*…*k.

### 3.Demo:


-Sudoku
