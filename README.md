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
Developed by: Yasvanth RD
RegisterNumber: 212224240189
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Yasvanth Rd
RegisterNumber: 212224240189
*/

# To print X matrix (solution to the equations)
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,piv=lu_factor(A)

x=lu_solve((lu,piv),B)

print(x)
```

## Output:

![450574980-3958e656-12b6-441f-8436-75b8e32bf5fb](https://github.com/user-attachments/assets/9092d343-ed11-41d6-85f2-2cca35afcc1c)
![450575043-056d3540-deba-47a3-9918-83fa961af6df](https://github.com/user-attachments/assets/556787f8-3963-48d7-b684-c00d131bacc6)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

