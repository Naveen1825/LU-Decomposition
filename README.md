# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### step 1:
import numpy as np
### step 2:
from scipy package import lu
### step 3:
get input from the user
### step 4:
print result
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Naveenkanthan L
RegisterNumber: 23007705
'''
import pprint
import scipy
import scipy.linalg

a=eval(input())
P,L,U=scipy.linalg.lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Naveenkanthan L
RegisterNumber: 23007705
'''

# To print X matrix (solution to the equations)
import numpy as np
a=eval(input())
b=eval(input())
print(np.linalg.solve(a,b))
```

## Output:
1st Program<br>
<img width="667" alt="290118035-90a1fe65-457c-411a-b936-9952f42786bb" src="https://github.com/Naveen1825/LU-Decomposition/assets/138969868/942255b0-1b62-4f11-a8d1-07da17ff0751"><br>
2nd Program<br>
<img width="668" alt="290118341-64607261-91ec-41a8-8104-1c03af82f20a" src="https://github.com/Naveen1825/LU-Decomposition/assets/138969868/edb6d577-b01e-47d3-87d8-db68a2cabe19">


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

