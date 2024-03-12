# hackerrank-python-sloution 
## Say "Hello, World!" With Python   

![alt text](https://github.com/AkashKobal/hackerrank-python-sloution/blob/main/questions/Say%20Hello%2C%20World!%20With%20Python.png)
```python
print("Hello, World!")  
```   
  
## Python If-Else 

![alt text](https://github.com/AkashKobal/hackerrank-python-sloution/blob/main/questions/Python%20If-Else.png)
```python 
import math
import os
import random
import re
import sys

if __name__ == '__main__':
    n = int(input().strip())
if n % 2 != 0:  
    print("Weird")  
elif n in range(2, 6):  
    print("Not Weird")  
elif n in range(6, 21):  
    print("Weird")  
else:  
    print("Not Weird") 
```
## Array reverse 
![alt text](https://github.com/AkashKobal/hackerrank-python-sloution/blob/main/questions/reverse%20array.png)
```python

import math
import os
import random
import re
import sys

#
# Complete the 'reverseArray' function below.
#
# The function is expected to return an INTEGER_ARRAY.
# The function accepts INTEGER_ARRAY a as parameter.
#

def reverseArray(a):
    ra = a[::-1]
    return ra
    # Write your code here

if __name__ == '__main__':
    fptr = open(os.environ['OUTPUT_PATH'], 'w')

    arr_count = int(input().strip())

    arr = list(map(int, input().rstrip().split()))

    res = reverseArray(arr)

    fptr.write(' '.join(map(str, res)))
    fptr.write('\n')

    fptr.close() 
```
