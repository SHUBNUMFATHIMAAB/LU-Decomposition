# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries
2. Read the matrix input and convert it into a NumPy array.
3. Apply LU decomposition using P, L, U = lu(A).
4. Print the Lower triangular matrix L and Upper triangular matrix U.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SHUBNUM FATHIMA AB
RegisterNumber: 212225240147
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P, L, U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: SHUBNUM FATHIMA AB
RegisterNumber: 212225240147
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu, piv=lu_factor(a)
x=lu_solve((lu, piv), b)
print(x)
```

## Output:
<img width="679" height="774" alt="image" src="https://github.com/user-attachments/assets/605ef8e9-18ee-4f03-b69e-ade637034dda" />
<img width="568" height="599" alt="image" src="https://github.com/user-attachments/assets/548b8ac5-b1e6-4d60-86a2-360f0a149673" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

