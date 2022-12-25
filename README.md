# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare a list for each linear equation and assign in numpy.linalg()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigenvalue and eigen vector using print() function.
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Aakashraj M
#RegisterNumber: 22008579

import numpy as np
a=np.array([[4,2],[2,4]])
w,v=np.linalg.eig(a)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:
![Ex-4 Output (1)](https://user-images.githubusercontent.com/121117266/209474822-aeed20d5-5b09-49f7-8baa-79ce4ad3d7a9.png)
![Ex-4 Output (2)](https://user-images.githubusercontent.com/121117266/209474831-7828be1d-bf53-40fb-ad9c-961b6621e1d4.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
