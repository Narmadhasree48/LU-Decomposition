# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step-1
Define the package as scipy.linalg import lu.
## step-2
Get input from user and print L and U matrix by 'print' .
## step-3
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
## step-4 
print the variable 'X'
## Step-5
End the program
## Program:
(i) To find the L and U matrix
```PYTHON
Program to find the L and U matrix.
Developed by:NARMADHA SREE S
RegisterNumber: 212223240105
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```PYTHON
Program to find the LU Decomposition of a matrix.
Developed by: NARMADHA SREE S
RegisterNumber: 212223240105
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
B= np.array(eval(input()))
lu, piv= lu_factor(A)
X= lu_solve((lu ,piv),B)
print(X)
```
## Output:
![alt text](<Screenshot 2024-04-20 115003.png>)
![alt text](<Screenshot 2024-04-20 115018.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

