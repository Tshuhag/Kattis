# Križaljka

Since ACTA has entered into force, Slavko has been spending his time offline, solving crosswords. Having solved\
almost all that he could get his hands on, he wants to make a few crosswords of his own. However, he is too sloppy\
for such fine work, so he has asked you to help him generate the crosswords.

You are given two words, *A* and *B*. The word *A* must be output horizontally, and the word *B* vertically, so that the\
two words cross (i.e., share exactly one letter). The shared letter must be the first letter in *A* that is also contained\
in *B*, more specifically the first occurrence of that letter in each word.

For example, given the words *A* = 𝙰𝙱𝙱𝙰 and *B* = 𝙲𝙲𝙱𝙱, you need to output 4 lines as shown below:

```
.C..
.C..
ABBA
.B..
```

## Input

The first and only line of input contains two words, *A* and *B*, not more than 30 characters long, separated by a\
single space. Both words will contain only uppercase English letters. There will be at least one letter contained in\
both words.

## Output

Let *N* be the length of word *A*, and *M* the length of word *B*. The output must contain *M* lines, each containing *N*\
characters. The character grid must contain the two words crossed as described above. All other characters in the\
grid must be periods (the character “.”, without quotes), thus padding all lines to the length of *N* characters.

| Sample Input        | Sample Output |
| ---                 | ---           |
| BANANA PIDZAMA      | .P....        |
|                     | .I....        |
|                     | .D....        |
|                     | .Z....        |
|                     | BANANA        |
|                     | .M....        |
|                     | .A....        |
|                     |               |
| MAMA TATA           | .T..          |
|                     | MAMA          |
|                     | .T..          |
|                     | .A..          |
|                     |               |
| REPUBLIKA HRVATSKA  | H........     |
|                     | REPUBLIKA     |
|                     | V........     |
|                     | A........     |
|                     | T........     |
|                     | S........     |
|                     | K........     |
|                     | A........     |