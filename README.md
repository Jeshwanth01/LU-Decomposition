# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
STEP 1:-
Define the package as scipy.linalg import lu.
STEP 2:-
Get input from user and print L and U matrix by 'print' .
STEP 3:-
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
STEP 4:-
Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JESHWANTH R
RegisterNumber: 2305003003
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JESHWANTH R
RegisterNumber: 2305003003
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:
![jesh 5](https://github.com/Jeshwanth01/LU-Decomposition/assets/145525167/7858f788-4e60-4ba3-a6a3-b1b236fd96ce)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

