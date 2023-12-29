# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function
2. Get the two matrix from the user
3. Return the Solution vector X

## Program:
(i) To find the L and U matrix
```
Program to solve a matrix using LU decomposition.
Developed by: CHANDRAPRIYADHARSHINI C
RegisterNumber: 23013526


#To print L and U matrix
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
Developed by: CHANDRAPRIYADHARSHINI C
RegisterNumber: 23013526


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/Bosevennila/LU-Decomposition/assets/144870486/ebb5eff0-d738-42e4-a602-ec39f349cc3a)
![image](https://github.com/Bosevennila/LU-Decomposition/assets/144870486/f09e9390-afb0-46a4-8797-5a8ef5f41e54)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

