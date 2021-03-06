# Primary Arithmetic

Children are taught to add multi-digit numbers from right-to-left one digit at a time. Many find the “carry”\
operation – in which a 1 is carried from one digit position to be added to the next – to be a significant challenge.\
Your job is to count the number of carry operations for each of a set of addition problems so that educators may\
assess their difficulty.

## Input

Each line of input contains two non-negative integers with less than 10 digits.

The last line of input contains 0 0. No other line contains 0 0. There are at most 50 lines of input.

## Output

For each line of input except the last you should compute and print the number of carry operations that would\
result from adding the two numbers, in the exact format shown below.

| Sample Input | Sample Output        |
| ---          | ---                  |
| 123 456      | No carry operation.  |
| 555 555      | 3 carry operations.  |
| 123 594      | 1 carry operation.   |
| 0 0          |                      |