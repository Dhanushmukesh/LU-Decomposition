# LU Decomposition 
DATE:30/03/2024

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

#Use LU Decomposition to find L and U matrix.INPUT:[[3,2,7],[2,3,1],[3,4,1]] '''program to find L and U matrix using LU decompostition.
Develeped by : Dhanush.G
RegisterNumber:2305002006
''' #To print L and U 
matrix import numpy as np 
from scipy.linalg import lu
A=np.array(eval(input())) 
P,L,U=lu(A) print(L) 
print(U)      

(ii) To find the LU Decomposition of a matrix

Use LU Decomposition to solve a matrix.INPUT:[[3,2,7],[2,3,1][3,4,1]]   [4,5,7] 
'''Program to find the LU Decomposition of a matrix.
Developed by: Dhanush.G
RegisterNumber: 2305002006
''' #To print X matrix(solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A) x=lu_solve((lu,piv),b)
print(x)
## Output:
![WhatsApp Image 2024-05-22 at 21 56 40_e207868a](https://github.com/Dhanushmukesh/LU-Decomposition/assets/155508176/9debd9b9-2772-4c49-aafb-fe9014990d9c)
![image](https://github.com/Dhanushmukesh/LU-Decomposition/assets/155508176/fd10b0cc-c75e-4279-b7f5-093fb2857f39)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

