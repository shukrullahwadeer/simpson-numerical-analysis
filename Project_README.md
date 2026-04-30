# Simpson’s 1/3 vs 3/8 Rule - Numerical Integration

## Project Title
Comparison of Simpson’s 1/3 Rule and Simpson’s 3/8 Rule for Numerical Integration

## Method Explanation
This project implements two numerical integration methods:

### Simpson’s 1/3 Rule
A numerical method that approximates integrals using quadratic polynomials over even intervals.

### Simpson’s 3/8 Rule
A higher-order method that uses cubic interpolation and requires the number of intervals to be divisible by 3.

The code compares the accuracy and stability of both methods using:
- sin(x)
- an oscillatory function: sin(10x) * exp(-x/2)

## Graph Outputs
The program generates two types of plots:

1. Error vs Number of Intervals (semi-log scale)
2. Convergence Rate (log-log scale)

These plots show that both methods converge to the exact solution, but their stability differs depending on the function behavior.
