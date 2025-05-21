# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U Matrix
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu
3. Enter the lists from each linear equations and assign in np.array() 
4. using lu() and store it in three variables
5. print the L and U Matrix 
6. End the program 

## Algorithm for LU Decomposition
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu_factor,lu_solve
3. Enter the lists from each linear equations and assign in np.array()
4. Enter the lists from each linear equations and assign in np.array()
5. using lu_factor() and store it in two variables
6. using lu_solve(),we can find L and U matrix
7. End the program 

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

