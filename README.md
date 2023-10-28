# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equation and assign in np.array()

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program. 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: saron xavier A
#RegisterNumber:23005103
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![rank of matrics](https://github.com/saron2006/RANK-OF-A-MATRIX/assets/138849343/9aaf247f-8651-4d5b-8ce1-c0c1a00b71b8)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

