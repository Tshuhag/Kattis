# Anthony and Diablo

Anthony has a pet hamster named Diablo. Diablo enjoys having lots of space to move around, so Anthony wants to\
build him a cage that covers as much area as possible.

However, Diablo also likes to dig and hide very much, and when he does, it is an absolute pain for Anthony to find\
Diablo (Diablo is very good at hiding). Therefore, Anthony wants to make sure the cage he builds for Diablo is not\
too big. In particular, Anthony wants to make sure the area of the cage is exactly *A* square meters; any area larger\
than *A* square meters will be too much work to find Diablo when he hides, any area smaller than *A* square meters\
will be too uncomfortable for Diablo.

Anthony has *N* meters of fencing that can be cut/bent at any point, and wonders if it is possible to build a cage of\
any shape that has area exactly *A* with the materials he has. Write a program to help him out!

## Input

The input contains two real numbers 0 < *A* ≤ 100 and 0 ≤ *N* ≤ 1000.

## Output

Output a single line with “Diablo is happy!” if Anthony can build his cage for Diablo, “Need more materials!”\
otherwise.

| Sample Input        | Sample Output           |
| ---                 | ---                     |
| 1.000000 4.000000   | Diablo is happy!        |
| 1.000000 0.000000   | Need more materials!    |