# Bits

As we all know, it takes more energy to store binary numbers with lots of ones in them. Yraglac’s calculator has\
some batteries that are almost dead, and he’s concerned that the battery may run out as he types in a number.

The way the calculator processes numbers being entered is as follows. Initially, the calculator stores the number\
zero in a 32-bit internal register. As Yraglac types in each digit of his number, the register updates to store the\
number entered thus far. For example, when Yraglac enters the number 94, the register stores the number 9\
(binary 1001) after the first key is pressed. When he presses the second key, the register clears itself and stores the\
number 94 (binary 1011110). What is the maximum number of one-bits in the register as Yraglac enters a number\
digit-by-digit?

To convert an integer x to a binary string, you can use Integer.toBinaryString(x) in Java and bin(x) in Python.\
See the language documentation for more information.

## Input

The first line contains a single integer *T* ≤ 1000 giving the number of test cases. Each test case consists of a line\
with a single integer *X* (0 ≤ *X* <2<sup>31</sup>), the number Yraglac wants to enter.

For each test case, output a single line containing the maximum number of one-bits in the storage register as the\
number *X* is entered, digit by digit.

| Sample Input | Sample Output |
| ---          | ---           |
| 6            | 1             |
| 1            | 1             |
| 2            | 2             |
| 3            | 1             |
| 4            | 2             |
| 10           | 5             |
| 94           |               |