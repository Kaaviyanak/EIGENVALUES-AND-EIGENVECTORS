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
#Developed by: K.KAAVIYAN
#RegisterNumber:212224240066
import numpy as np

# Define the matrix
A = np.array([[2, 2],
              [1, 3]])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Display the results
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
![Screenshot 2025-04-26 142346](https://github.com/user-attachments/assets/f94a67a1-b212-4aed-b90b-a6cf7a1ffe88)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
