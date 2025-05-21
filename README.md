# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the NumPy module to access linear algebra functions.
### Step 2:
Create a matrix using np.array() with the desired rows and columns.
### Step 3:
Use np.linalg.matrix_rank() to compute the rank of the matrix.
### Step 4:
Display the rank using a print statement.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: BALA B
#RegisterNumber:212224100005
import numpy as np
matrix = np.array([[1, 2, 3], [3, 6, 9]])
rank = np.linalg.matrix_rank(matrix)
print(rank)
```
## Output:

![image](https://github.com/user-attachments/assets/a48b3afa-d27b-45b3-80a4-63f87b0e5aa6)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

