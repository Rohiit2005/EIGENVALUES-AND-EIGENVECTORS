# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy moduleto use the built-in function for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the prigram

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rohiit.A.S
#RegisterNumber:23010688
import numpy as np
a=np.array([[2,2,],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:![exp4](https://github.com/Rohiit2005/EIGENVALUES-AND-EIGENVECTORS/assets/138849178/40cf2202-e3fc-49f6-ba89-bf6133eca8e3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
