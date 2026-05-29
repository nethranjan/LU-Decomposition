# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: D R NETHRANJAN CHOWDARY
RegisterNumber: 
*/
import os
os.environ['OPENBLAS_NUM_THREADS'] = '1'
os.environ['OMP_NUM_THREADS'] = '1'
os.environ['MKL_NUM_THREADS'] = '1'
import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: D R NETHRANJAN CHOWDARY
RegisterNumber: 212225100031
*/
import os
os.environ['OPENBLAS_NUM_THREADS'] = '1'
os.environ['OMP_NUM_THREADS'] = '1'
os.environ['MKL_NUM_THREADS'] = '1'
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix= np.array(eval(input()))
constant= np.array(eval(input()))
piv,lu= lu_factor(matrix)
result= lu_solve((piv,lu),constant)
print(result)

```

## Output:
(i)<img width="1118" height="930" alt="Screenshot 2026-05-29 171141" src="https://github.com/user-attachments/assets/a2025bbd-4c53-4428-9d9b-d0b5b5ffe1c4" />

(ii) <img width="1480" height="899" alt="Screenshot 2026-05-29 171154" src="https://github.com/user-attachments/assets/df2e795b-137b-491c-b34a-1e7601c9d3c2" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

