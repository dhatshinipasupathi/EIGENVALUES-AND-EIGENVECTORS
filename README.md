# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start the program
### Step 2: Import the Numpy library and create the given matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors and stop the program

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by: dhatshini p
### RegisterNumber:26010141
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A = np.array([[2,2],[1,3]])
### values,vector = np.linalg.eig(A)
### print(f"Eigen values are {values} and Eigen Vectors are {vector}")
## Output:
<img width="1235" height="827" alt="Screenshot 2026-10-13 160501" src="https://github.com/user-attachments/assets/d3c214d2-d093-46d1-a8fa-a5e697b3201e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
