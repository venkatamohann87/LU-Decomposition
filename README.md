# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### (i) To find the L and U matrix
### Step 1:
Import the necessary libraries: NumPy as np and lu from SciPy's linalg module.
### Step 2:
Take matrix input from the user, convert it into a NumPy array A using eval(input()).
### Step 3:
Perform LU decomposition on matrix A to obtain matrices P, L, and U using lu(A).
### Step 4:
Print the lower triangular matrix L and the upper triangular matrix U. 
### (ii) To find the LU Decomposition of a matrix.
### Step 1:
Import the required libraries: NumPy as np and lu_factor, lu_solve from SciPy's linalg module.
### Step 2:
Take matrix input A and vector input b from the user and convert them into NumPy arrays.
### Step 3:
Compute the LU decomposition of matrix A using lu_factor(A) and store the LU matrix and pivot indices.
### Step 4:
Solve the system of linear equations Ax = b using lu_solve((lu, piv), b) and print the solution vector X.



## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: VENKATA MOHAN N
RegisterNumber: 212224230298
*/
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: VENKATA MOHAN N
RegisterNumber: 212224230298
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```

## Output:

### (i):To find the L and U matrix
![Screenshot 2025-04-27 142931](https://github.com/user-attachments/assets/a358efa9-a1c9-464f-b393-47897cd50b81)




### (ii):To find the LU Decomposition of a matrix




![Screenshot 2025-04-27 142943](https://github.com/user-attachments/assets/f135ca90-9aae-4c07-9ec1-789405e7e006)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
