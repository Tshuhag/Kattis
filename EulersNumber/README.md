# Euler's Number

Euler’s number (you may know it better as just e) has a special place in mathematics. You may have encountered *e*\
in calculus or economics (for computing compound interest), or perhaps as the base of the natural logarithm, lnx,\
on your calculator.

While e can be calculated as a limit, there is a good approximation that can be made using discrete mathematics.

Note that 0!=1. Now as n approaches ∞, the series converges to e. When n is any positive constant, the formula\
serves as an approximation of the actual value of e. (For example, at n=10 the approximation is already accurate\
to 7 decimals.)

You will be given a single input, a value of n, and your job is to compute the approximation of e for that value of n.

## Input

A single integer n, ranging from 0 to 10000.

## Output

A single real number – the approximation of e computed by the formula with the given n. All output must be\
accurate to an absolute or relative error of at most 10−12.

| Sample Input | Sample Output        |
| ---          | ---                  |
| 3            | 2.6666666666666665   |
| 15           | 2.718281828458995    |