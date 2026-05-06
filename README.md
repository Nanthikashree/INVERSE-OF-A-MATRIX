# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy library
### Step 2: decare array of matrix
### Step 3: using linalg.inv function find the inverse of the matrix
### Step 4: 

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Nanthikashree T
#RegisterNumber:212225040274
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(matrix)
print(inverse)
```
## Output:
<img width="806" height="925" alt="image" src="https://github.com/user-attachments/assets/ea62cefe-7e2b-428f-86c5-b1da130134f9" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

