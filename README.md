# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Inthe first stepnto find lu decomposition we using import numpy as np
2.Next we using scipy.linalg for import 
3.Next we setting the variable name 
4. Finally printing the value

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

/*
Program to find the L and U matrix.
Developed by:panimalar.p 
RegisterNumber: 22009107
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:panimalar.p 
RegisterNumber: 22009107
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)

```

## Output:

![Screenshot (173)](https://user-images.githubusercontent.com/121490826/214630963-c235c2d2-278b-4c02-a842-c3ff900b5088.png)

![Screenshot (174)](https://user-images.githubusercontent.com/121490826/214631049-2697b1e2-4971-4ed3-9d12-8602db78d359.png)


![Screenshot (170)](https://user-images.githubusercontent.com/121490826/214630163-fbbb076e-f810-41b1-a3e6-623e8df6bc74.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

