# LU Decomposition 
DATE:

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 	import the NumPy library using the statement import numpy as np.
2.	Define the given matrix A
3.	Compute the LU Decomposition using np.linalg.inv()
4.	print and end the program
## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decompostition.
Develeped by : Dhanush.G
RegisterNumber:2305002006

import numpy as np 
from scipy.linalg import lu
A=np.array(eval(input())) 
P,L,U=lu(A) print(L) 
print(U)
```

(ii) To find the LU Decomposition of a matrix
 ```
Program to find the LU Decomposition of a matrix.
Developed by: Dhanush.G
RegisterNumber: 2305002006

import numpy as np
from scipy.linalg import lu_factor,lu_solve A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A) x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![WhatsApp Image 2024-05-22 at 21 56 40_e207868a](https://github.com/Dhanushmukesh/LU-Decomposition/assets/155508176/9debd9b9-2772-4c49-aafb-fe9014990d9c)
![33](https://github.com/Dhanushmukesh/LU-Decomposition/assets/155508176/db7d280a-faa4-404e-b269-6ec37e0e98b9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

