# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[4,2],[2,4]])
eig_values,eig_vectors=np.linalg.eig(a)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vectors}")
```
## Output:
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/dd41073e-c6ce-4c0d-9259-f706ee8c0986" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
