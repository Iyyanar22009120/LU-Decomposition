# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as num
2. get arr
3. assume A as np.array(arr)
4. print L and U

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.IYYANAR
RegisterNumber:22009120
import numpy as np  #form numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.IYYANAR
RegisterNumber: 22009120
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
(i)output of program to find the L and U matrix.![lu decomposition](./LU%20Decomposition%201.png)
(ii)output of program to find the LU decomposition of a matrix![lu decomposition](./LU%20Decomposition%202.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

