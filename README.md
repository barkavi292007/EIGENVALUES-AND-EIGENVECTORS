# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm:

### Step 1:

Import the numpy module.

### Step 2:

Create the matrix using `np.array()`.

### Step 3:

Use `np.linalg.eig()` to find the Eigenvalues and Eigenvectors of the matrix.

### Step 4:

Print the Eigenvalues and Eigenvectors.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:BHARGAVI S 
#RegisterNumber:212225230033
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2,2],[1,3]])

values, vectors = np.linalg.eig(A)

print("Eigen values are", values, "and Eigen Vectors are", vectors
```

## Output:
<img width="1240" height="805" alt="Screenshot 2026-05-14 112556" src="https://github.com/user-attachments/assets/4822ee23-2139-4be7-99fc-32ed0266f5a5" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
