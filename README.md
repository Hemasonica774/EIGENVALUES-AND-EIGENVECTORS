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

#Program to find the eigen values and eigen vectors.
#Developed by:Hema sonica.P 
#RegisterNumber:22003246
import numpy as np
A = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:

![image](https://user-images.githubusercontent.com/118361409/213133172-167ecea3-a425-4283-9738-c4ef968c3540.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
