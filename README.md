# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step 1:start .
## step 2:get an input from user. 
## step 3: display the value  .
## step 4:stop.

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: anandhamoorthy
RegisterNumber: 212222100004
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: anandhamoorthy
RegisterNumber: 212222100004
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![lu decomposition]()
1)![Screenshot 2023-06-08 125304](https://github.com/AnandhamoorthyKarthikeyan/LU-Decomposition/assets/119475998/658b3c0a-13d0-4cf6-b022-25a5d033da2b)
2)![Screenshot 2023-06-08 125315](https://github.com/AnandhamoorthyKarthikeyan/LU-Decomposition/assets/119475998/0661fa85-df71-4c70-9ab9-5416c477f4f8)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

