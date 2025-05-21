# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy which has built-in function for matrix operation 
### Step 2: Represent the matrix as a 2D numpy array 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
``````
#Program to find the eigen values and eigen vectors.
#Developed by: KAAVIYAN.K
#RegisterNumber:24006507
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvector=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvector)
``````
## Output:
![Screenshot 2025-05-21 084130](https://github.com/user-attachments/assets/aeb2ddae-11c2-4a8a-a5c8-bba202d00fa0)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
