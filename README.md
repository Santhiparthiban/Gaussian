# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Step 1: Import the numpy module to use the built-in function for calculation
2.Step 2: prepare the list from matrix and assign in np.array()
3.Step 3: Using lu_solve and lu_factor we can find the solution
4.Step 4:End the program

## Program:
Program to find L and U matrix using LU decomposition.
Developed by: P.SANTHI
RegisterNumber: 25004254
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
/*
Program to find the solution of a matrix using Gaussian Elimination.
Developed by: P.SANTHI
RegisterNumber: 25004254
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
## Output:
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/907196c9-bfff-4f53-9d55-c061a4bcd3e2" />
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/1fc17ab8-662e-4b26-a6be-0699ec949ae1" />

## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

