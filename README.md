## Problem Statement:

You are given a system of linear equations in the form:

Ax + By + Cz + ... = k   -- (1)

The input consists of the following:

- The first line contains an integer 'n' representing the number of variables.
- The next 'n' lines contain 'n' equations in the form of equation (1).
- The (n+1)-th line contains 'n' coefficients A, B, C, ... and the constant term k.

The goal is to find the values of x, y, z, ... that satisfy the system of equations. The output should be formatted as follows:

- If the system of equations is not solvable, output "NO".
- If the system is solvable, output "YES" and the values of x, y, z, ... with two decimal places.

## Input Format Example:

```
3
2 1 -1 8
-3 4 2 1
1 -1 3 6
2 3 -1
```

## Output Format Example:

```
YES
2.00 -1.00 3.00
```

## Explanation:

In the given example, the system of equations is solvable. The values of x, y, z are 2.00, -1.00, and 3.00, respectively. The output is formatted with two decimal places. If the system were not solvable, the output would be "NO".
