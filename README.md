# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the library numpy using the import command.
### Step 2: 
Assinging a matrix to a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the inverse of the matrix and end the program. 
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Gorisankar.p
#RegisterNumber: 212222230041

import numpy as np
from numpy.linalg import eig
a=np.array([[2,2],[1,3]])
w,v=eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(w,v))
```
## Output:
![Screenshot (77)](https://user-images.githubusercontent.com/119393123/227961153-ba1fd399-f038-4113-acf5-a1b0f64fb580.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
