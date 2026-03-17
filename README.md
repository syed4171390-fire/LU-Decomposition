# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation 
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions. 
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Syed Shamsheer Ali
RegisterNumber: 212225220114
import numpy
from scipy.linalg import lu
matrix = eval(input())
P, L, U = lu(matrix)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Syed Shamsheer Ali
RegisterNumber: 212225220114
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
![image](<img width="1508" height="814" alt="Screenshot 2026-03-17 101033" src="https://github.com/user-attachments/assets/ce205e40-14ca-4d0c-89d9-f0226d342828" />)![image](<img width="1511" height="636" alt="Screenshot 2026-03-17 101049" src="https://github.com/user-attachments/assets/f9286877-1dcb-4419-9d96-6265fd3089d0" />)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

