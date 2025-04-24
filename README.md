# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' . 
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.

Developed by: Venkata mohan N

RegisterNumber: 212224230298

'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.

Developed by: Venkata Mohan N

RegisterNumber: 212224230298
'''

# To print X matrix (solution to the equations)


import numpy as np
from scipy .linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:

![image](https://github.com/user-attachments/assets/f5cecf02-ece7-4289-b130-ee149d4151f8)

![image](https://github.com/user-attachments/assets/3c81af20-edab-45cd-99b8-899b66ce827f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

