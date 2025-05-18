# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start with the given matrix.

### Step 2:Convert the matrix into row echelon form using row operations.

### Step 3:Identify rows that are completely zero.

### Step 4:Count the number of non-zero rows.

### Step 5:That count is the rank of the matrix.


## Program:
```
#Program to find the rank of a matrix.
#Developed by:BALA B
#RegisterNumber: 212224100005
import numpy as np
A = [[1,2,3],[3,6,9]]
sln = np.linalg.matrix_rank(A)
print(sln)
```
## Output:

![image](https://github.com/user-attachments/assets/a48b3afa-d27b-45b3-80a4-63f87b0e5aa6)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

