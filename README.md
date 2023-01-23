# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import numpy package.
### Step 2:Find eigenvalues and  then find eigenvectors. 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Hema sonica.P 
#RegisterNumber:22003246

import numpy as np
A = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![Screenshot (85)](https://user-images.githubusercontent.com/118361409/214043033-40f23c75-bec0-4aba-9a6f-a934c31f9f95.png)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
