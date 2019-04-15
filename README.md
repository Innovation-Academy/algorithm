1.先确认前条件/不变式/终止条件/边界条件，然后写出正确的代码

# 面试考试
1. 考察面试者的编码能力
# 题型
string、binary search，linked list，divide conquer，array，breadth first search，depth first search



# Algorithmic Paradigms [1]

## Divide and Conquer
Idea: Divide a problem into two or more sub-problems, solve these recursively, and then put solutions together to a solution of the given problem.

Examples: Mergesort, Quicksort, Strassen’s algorithm for matrix multiplication, FFT.

## Dynamic Programming
Idea: Break up a problem into a series of overlapping
 sub-problems, and build up solutions to larger and larger sub-problems. 
prune and search for  solving optimization problems
another idea：Brute force through all possible solutions, storing solutions to
subproblems to avoid repeat computation

Example: Floyd-Warshall algorithm for the all pairs shortest path problem

## Backtracking
– A clever form of exhaustive search

## Greedy Algorithms

Idea: Find solution by always making the choice that looks optimal at the moment — don’t look ahead, never go back.
Examples: Prim’s algorithm and Kruskal’s algorithm for a minimum spanning tree. Shortest path


# 链表专题
目的：考察思维全面性和写无BUG代码的能力
1. 多指针协同工作（前指针和后指针，快指针和慢指针）
2. 头节点有可能改变的需引入dummy节点
3. 尽量 in space     尽量避免O(n2)
4. 写code时，注意null节点


Reference:
1. https://courses.cs.washington.edu/courses/cse373/16wi/slides/22-Algorithm-Design.pdf
