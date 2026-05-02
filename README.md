# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: Devadhaarini.R 
#RegisterNumber: 212225040061.
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA = np.array([[2, 2],[1, 3]])
eigen_value,eigen_vector=np.linalg.eig(matrixA)
print("Eigen values are",eigen_value ,"and Eigen Vectors are",eigen_vector)
~~~

## Output:
<img width="1920" height="1080" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/d376f10d-d6fd-477d-8e30-e61671b44173" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
