# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
import  numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
Developed by: Arunraj R
RegisterNumber: 212224110006
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
L,P=lu_factor(a)
x=lu_solve((L,P),b)
print(x)
Developed by: Arunraj R
RegisterNumber: 212224110006
*/
```

## Output:
<img width="1288" height="929" alt="Screenshot 2025-08-28 093718" src="https://github.com/user-attachments/assets/f1cfa7bb-6849-4990-9f5d-4ec7bfaa3706" />
<img width="1293" height="886" alt="Screenshot 2025-08-28 093752" src="https://github.com/user-attachments/assets/7bcd9cb9-8d08-468a-a02d-0e699e0762fc" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

