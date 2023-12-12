# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the listfrom each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```python
#Developed by: Swaminathan V
#RegisterNumber: 23000747

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![4-Eigen values](https://github.com/SwaminathanV23000747/EIGENVALUES-AND-EIGENVECTORS/assets/148931113/51b14a1c-d16e-4612-a017-4eb90dda9d16)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
