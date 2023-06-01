# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import numpy module 
## Step 2:
Get input matrice from the user
## Step 3:
Use lu funtion
## Step 4:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Vanitha
RegisterNumber: 212222100057
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Vanitha S
RegisterNumber: 212222100057
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![image](https://github.com/Vanitha-SM/LU-Decomposition/assets/119557985/78e51bf8-4baf-488f-be89-f265ff5a8220)
![image](https://github.com/Vanitha-SM/LU-Decomposition/assets/119557985/a6d438a8-d379-4da8-8402-1be0da2ad2b7)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

