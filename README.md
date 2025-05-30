# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import required libraries numpy and scipy.linalg.

2. Input the matrix/matrices using eval(input()).

3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

4. Print the results L and U matrices or solution X matrix

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Karthikraj C
RegisterNumber: 212224230027

import numpy as  np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Karthikraj C
RegisterNumber: 212224230027

To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
piv,lu=lu_factor(A)
result=lu_solve((piv,lu),B)
print(result)
```

## Output:
![lu decomposition]()
![alt text](<Screenshot 2025-05-21 101848.png>) 
![alt text](<Screenshot 2025-05-21 101859.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

