# Dai Ke Tech Interview Test

## Introduction

Congratulation for you pass the first phase interview! The following tech interview is an opportunity to show how well your programming skills are.

The test is base on some online judge sytem problems like LeetCode or ACM online judge.

### Requirement

* Write simple function to solve following questions efficiently and correctly.
* You can use any programming language during the test, but it should present your algorithm PRECISELY.
* Please commit all code to github, and send the repository URL back after the test.
* For every question you complete, the unit tests is REQUIRED.

### Our Expectations

Through this programming test, you should be able to demonstrate:

1. Good understand of the programming you used.
2. Good programming practices. Code quality and maintainability.
3. Good understand of unit tests.
2. Apply suitable algorith to solve this questions.
3. A good result! Our average number of problems solved is about 3. Show how well you can do!

### Ask for Help

Should you have any questions, shoot us an email any time.

We highly encourage you to do so, even if you needed help solving the problem. Apart from examining your programming skills, we also want to see what it looks like working with you.

## Questions

### 1. Product array

Given an array of n integers where n > 1, nums, return an array output such that output[i] is equal to the product of all the elements of nums except nums[i].

Solve it without division and in O(n).

For example, given [1,2,3,4], return [24,12,8,6].

### 2. Number first

Given an array nums, write a function to move all non-zero numbers to the head of it while maintaining the relative order of the non-zero numbers.

For example, given nums = [0, 1, 0, 3, 12], after calling your function, nums should be [1, 3, 12, 0, 0].

Note:
You must do this in-place without making a copy of the array.
Minimize the total number of operations.

### 3. Game of Life

According to the Wikipedia's article: "The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970."

Given a board with m by n cells, each cell has an initial state live (1) or dead (0). Each cell interacts with its eight neighbors (horizontal, vertical, diagonal) using the following four rules (taken from the above Wikipedia article):

1. Any live cell with fewer than two live neighbors dies, as if caused by under-population.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by over-population..
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.
Write a function to compute the next state (after one update) of the board given its current state.

Follow up: 

- Could you solve it in-place? Remember that the board needs to be updated at the same time: You cannot update some cells first and then use their updated values to update other cells.
- In this question, we represent the board using a 2D array. In principle, the board is infinite, which would cause problems when the active area encroaches the border of the array. How would you address these problems?

### 4. Simple root square

Implement int sqrt(int x).

Compute and return the square root of x.

### 5. Power

Implement pow(x, n).
