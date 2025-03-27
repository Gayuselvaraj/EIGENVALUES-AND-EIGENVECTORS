# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: get the input from user
## Step 2: import math and initialise the two values
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.
## Step 4:print the values in format

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: GAYATHRI S
#RegisterNumber:212224230073
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:

![Screenshot 2025-03-23 114158](https://github.com/user-attachments/assets/a7f627bf-ec29-4227-8c5b-11e210a69d1d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
