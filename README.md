# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Using numpy and scipy.linalg library to calculate the L and U decomposition.
2. get the input form the user.
3. Using lu_factor() and lu_solve() function to solve the lu decomposition.
4. print the output of the lu decomposition program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Arunkumar S
RegisterNumber: 24900773
*/
import numpy as np
from scipy.linalg import lu
A=np.array (eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Arun kumar S
RegisterNumber: 24900773
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array (eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()
![Screenshot 2024-11-28 201909](https://github.com/user-attachments/assets/904e5e15-9bd5-457a-b5a1-12f7b4550490)
![Screenshot 2024-11-28 201920](https://github.com/user-attachments/assets/4321c3ea-656e-479b-b358-71365ff8b5e6)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

