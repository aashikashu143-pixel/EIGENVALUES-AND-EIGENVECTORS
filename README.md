# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: AASHIK.A
#RegisterNumber:212225040005


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Define the matrix
A = np.array([[4, 2],
              [2, 4]])

# Find eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Display the result
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

```

## Output:

<img width="1500" height="875" alt="Screenshot 2026-06-02 134754" src="https://github.com/user-attachments/assets/58484364-2ae2-4d8e-bc89-f7ae15dc69a7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
