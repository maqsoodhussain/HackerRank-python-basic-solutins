# HackerRank-python-basic-solutins


##   Problem 1:
    Here is a sample line of code that can be executed in Python:

print("Hello, World!")
You can just as easily store a string as a variable and then print it to stdout:

my_string = "Hello, World!"
print(my_string)
The above code will print Hello, World! on your screen. Try it yourself in the editor below!

Input Format

You do not need to read any input in this challenge.

Output Format

Print Hello, World! to stdout.

Sample Output 0

Hello, World!

solution : 
```
if __name__ == '__main__':
    print("Hello, World!")

```



## Problem 2 :
Sample Input 0

3
Sample Output 0

Weird
Explanation 0
n=3

 n is odd and odd numbers are weird, so print Weird.

Sample Input 1

24
Sample Output 1

Not Weird
Explanation 1
n = 24

 n > 20 and n is even, so it is not weird.

 solution :
 ```
import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
    if n % 2 != 0:
        print("Weird")
    elif  n >= 2 and n <= 5:
        print("Not Weird")
    elif n >= 6 and n <= 20:
        print("Weird")
    elif n >= 20:
        print("Not Weird")
```
