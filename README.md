# GDG FOSS Wing: Easy Task

Welcome to the **FOSS** Section! 

## Problem Statement
You are given two positive integers $n$ and $k$. Your task is to find and print the $k$-th positive integer that is **not** divisible by $n$.

For example, if $n = 3$ and $k = 7$, then all numbers that are not divisible by $3$ are: $1, 2, 4, 5, 7, 8, 10, 11, 13 \dots$ 
The 7th number among them is $10$.

## Input Format
* The first line contains an integer $t$ ($1 \le t \le 1000$) — the number of test cases.
* Each of the next $t$ lines contains two integers $n$ and $k$ ($2 \le n \le 10^{15}$, $1 \le k \le 10^{15}$).

## Output Format
For each test case, print the $k$-th non-divisible integer on a new line.

## Example

**Input:**
```text
4
3 7
4 12
2 1
10 26
```

**Output:**
```text
10
15
1
28
```

## Your Mission
There is a `solution.cpp` file already provided in this directory. 

To complete this task:
1. Verify if the provided solution is correct.
2. Ensure it can pass our automated CI checks.
3. Submit a Pull Request with the exact working version.

*Note: If the current code fails the automated tests, remember that version control is a time machine! The optimal logic might already exist somewhere in the project's history.*