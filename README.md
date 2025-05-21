# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
import numpy as np
### Step 2:
from scipy package import lu
### Step 3:
get input from the user
### Step 4:
print result
## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: MOHAMMED ASHFAQ NADEEM A
RegisterNumber: 212224230166
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: MOHAMMED ASHFAQ NADEEM A
RegisterNumber: 212224230166
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)

```

## Output:
![Screenshot 2025-05-21 083104](https://github.com/user-attachments/assets/3addc235-c918-4857-b750-cc2c90a9a770)
![Screenshot 2025-05-21 083120](https://github.com/user-attachments/assets/f8b71ecc-f0a0-4fe3-a084-0d2327c75ca4)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

