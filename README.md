# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy module as np and lu from scipy
2. get the input from the user
3. find lu using inbuit functions
4. print the output

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: vivek christo A
RegisterNumber: 212225040497
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: vivek christo A
RegisterNumber: 212225040497
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1125" height="372" alt="Screenshot 2026-02-07 082347" src="https://github.com/user-attachments/assets/0b04a68d-4261-41ef-8038-6942083a19fd" />



<img width="851" height="129" alt="Screenshot 2026-02-07 082357" src="https://github.com/user-attachments/assets/5158a245-862b-4461-bcec-2d62a94b9a21" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

