# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define the package as scipy.linalg import lu.
### Step 2:
Get input from user and print L and U matrix by 'print' .
### Step 3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
### Step 4:
print the variable 'X'

## Program:
### (i) To find the L and U matrix
```
*/
#Program to solve a matrix using LU decomposition.
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
#Developed by:Tharun V K 
#RegisterNumber:212223230231 
*/
```
### (ii) To find the LU Decomposition of a matrix
```
/*
#Program to find the LU Decomposition of a matrix.
import numpy as np
from scipy. linalg import lu_ factor, lu_solve
A = np array (eval (input ()))
B = np. array(eval(input ()))
lu, pive lu factor (A)
x = lu solve((lu, piv), B)
print (x)
#Developed by: Tharun V K
#RegisterNumber: 212223230231
*/
```

## Output:
### (i) To find the L and U matrix
![alt text](<Screenshot 2024-04-17 191738.png>)

### (ii) To find the LU Decomposition of a matrix
![alt text](<Screenshot 2024-04-17 191755.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

