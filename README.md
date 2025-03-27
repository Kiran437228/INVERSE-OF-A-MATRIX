# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the math module as np
### Step 2: Store the array in variable A
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Substitute the matrix for rank using module function 

## Program:
```
#Program to find the inverse of a matrix.

#Developed by: KIRAN KUMAR CS

#RegisterNumber:212224240076

import numpy as np

A=np.array([[2,1,1],[1,1,1],[1,-1,2]])

inverse=np.linalg.inv(A)

print(inverse)
```
## Output:
![image](https://github.com/user-attachments/assets/d46c5691-175d-473c-a0b1-1a560dcd17b4)

## Result:
Thus the inverse of given matrix is successfully solved using python program

