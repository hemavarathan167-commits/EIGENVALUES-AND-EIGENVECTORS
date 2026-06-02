# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : Import required libraries
## Step 2: Create the matrix using NumPy array
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: Sort eigenvalues and eigenvectors

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0, 3]])

eigen_values, eigen_vectors = np.linalg.eig(A)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
```
## Output:
<img width="1287" height="171" alt="{F6E0A691-7CD0-4E15-82F2-9FBBA1616CE6}" src="https://github.com/user-attachments/assets/308d0f34-01ce-4d03-b24d-b837c7c0d23c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
