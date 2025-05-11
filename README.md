# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3. Perform scipy.linalg.lu to find the pivot table, lower triangle and upper triangle matrix.
4. End the Program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Vishvanandh N
RegisterNumber: 212224240186
*/
from scipy.linalg import lu
a = eval (input())
p,l,u =lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Vishvanandh N
RegisterNumber: 212224240186
*/
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
a=eval(input())
b=eval(input())
lu,plv=lu_factor(a)
x=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:


![Screenshot 2025-05-11 203051](https://github.com/user-attachments/assets/67f9850c-f4d4-4ccf-8246-6ea5864bb657)

![Screenshot 2025-04-15 161841](https://github.com/user-attachments/assets/6e47ea04-8d5d-4780-9d49-41f9f6072370)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

