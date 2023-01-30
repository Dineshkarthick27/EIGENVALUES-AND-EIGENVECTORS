# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen Vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors,then end the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Dinesh Karthick.K.J
#RegisterNumber:22005847
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://user-images.githubusercontent.com/120552008/215486214-4bd5d650-8796-4879-bad5-1cad37754c7d.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
