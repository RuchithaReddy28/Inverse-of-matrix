# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of matrix.

## EQUIPEMENT'S REQUIRED:
PC Anaconda-Python 3.7

## ALGORITHM:
### Step 1:
Use import numpy as np.

### Step 2:
Enter the input.

### Step 3:
Use for loop and range.

### Step 4:
Use np.linalg.inv() to find inverse of matrix.

### Step 5:
print()


## PROGRAM:
Name:A.Ruchitha Reddy

Ref.no:21005032

```python
import numpy as np
l1,l2=[],[]
r=int(input())
c=int(input())
for i in range (r):
    for j in range (c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse=np.linalg.inv(value1)
print(inverse)
```

## OUTPUT:
![output]()

## RESULT:
Thus the program is written to find the matrix.
