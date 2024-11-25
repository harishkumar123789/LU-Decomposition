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
Program to find the L and U matrix. 
Developed by:Harish Kumar S
RegisterNumber:24010415 
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
Developed by: 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![alt text](<Screenshot 2024-11-25 140915.png>)
![alt text](<Screenshot 2024-11-25 140929.png>)
![alt text](<Screenshot 2024-11-25 140947.png>)
![alt text](<Screenshot 2024-11-25 141000.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

