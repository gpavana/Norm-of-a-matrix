# Norm of a matrix
## DATE:03.10.2023
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212222230105
# Developed By:PAVANA G

# 1-Norm of a Matrix:

import numpy as np
a=eval(input())
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix:

import numpy as np
a=eval(input())
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix:

import numpy as np
a=eval(input())
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/gpavana/Norm-of-a-matrix/assets/118787343/d4b22fd9-8588-485d-abc1-f7957f595c11)
### 2-Norm of a Matrix
![image](https://github.com/gpavana/Norm-of-a-matrix/assets/118787343/68f9ad31-4a95-44c8-87d3-d7171933b3d3)
### Infinity Norm of a Matrix
![image](https://github.com/gpavana/Norm-of-a-matrix/assets/118787343/caa5c7cb-f046-4a7b-a68c-a278a8c28dd6)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
