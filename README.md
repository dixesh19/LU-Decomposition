# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
import numpy as np
### Step 2:
from scipy package import lu
### Step 3:
get input from the user
### Step 4:
print result
## Program:
(i) To find the L and U matrix
```
"""Program to find L and U matrix using LU decomposition.
Developed by: DINESH R
RegisterNumber: 212224240037
"""

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: DINESH R
RegisterNumber: 212224240037
'''

# To print X matrix (solution to the equations)
import numpy as np

from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input()))

b = np.array(eval(input()))

lu, piv = lu_factor(A)

X = lu_solve((lu, piv),b)

print(X)


```

## Output:
![image](https://github.com/user-attachments/assets/7dba53de-b512-43f0-bfb6-78019f7801a1)
![image](https://github.com/user-attachments/assets/4c474b99-7c92-465e-ab78-cd90d62a1d5c)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

