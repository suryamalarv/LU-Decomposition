# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: suryamalarv
RegisterNumber: 23013656
*/
```
```
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: suryamalarv
RegisterNumber: 23013656
*/
```
```
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```
```
```

## Output:

i)
![Screenshot 2023-12-17 145238](https://github.com/suryamalarv/LU-Decomposition/assets/145742486/70bdc302-4001-47b6-887b-bda755cabdfa)
ii)
![Screenshot 2023-12-17 145142](https://github.com/suryamalarv/LU-Decomposition/assets/145742486/f276ea55-eae0-4cae-b90a-c00b84d561b5)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.



