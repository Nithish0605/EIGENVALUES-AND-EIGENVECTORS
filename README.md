# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : get the input from user

### Step 2: import math and initialise the two values 

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: NITHISH S 
#RegisterNumber:212224240105

import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)
```

## Output:

<img width="1212" height="250" alt="image" src="https://github.com/user-attachments/assets/c90756d7-3fcf-497c-b141-78a6fe1d7f51" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
