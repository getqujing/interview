# Dai Ke Tech Interview Test

## Introduction

Thanks for spending time taking the tech interview. It is an opportunity to show how awesome you are at programming.

Usually, we have 3 - 4 rounds of interviews:

1. Preliminary tech interview (this round, Skype/phone)
2. Advanced tech interview (1 - 2 rounds, Skype/phone)
3. Interview with the team (on-site)

In most cases, it takes 2 - 3 weeks to complete the process.

Questions in the preliminary test stem from online judge system platform like LeetCode，or international programming contest like ACM.

### Requirements

* Keep your code neat, concise, and readable.
* Use any programming language of your choice.
* Commit your code to Github, and send the repository URL back.
* Unit test(s) is REQUIRED for every question.
* You only have one hour! Don't worry, most well-trained developers could do this.

### Our Expectations

In this programming test, you should demonstrate:

1. Good understanding of the programming language you use.
2. Good programming practices. Code quality and maintainability.
3. Good understanding of unit tests.
4. Good understanding of algorithms.

### Ask for Help

Should you have any questions, shoot us an email.

We highly encourage you to do so, even if you need further assistance to overcome these programming hurdles. Apart from examining your programming skills, we also want to see what it looks like to work with you.

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
