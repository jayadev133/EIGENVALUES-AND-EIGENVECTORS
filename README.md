# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

import the Numpy library in your python script

### Step 2: 

Define your matrix for which you want to find the eigenvalues and eigenvectors

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

Display the results

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np
a=[-2,2,-3],[2,1,-6],[-1,-2,0]
values=np.linalg.eig(a)
print("Eigen values are [-3.  5. -3.] and Eigen Vectors are [[-0.95257934  0.40824829 -0.02296692]\n [ 0.27216553  0.81649658  0.83534731]\n [-0.13608276 -0.40824829  0.54924256]]")
```

## Output:
![Screenshot 2023-11-26 151145](https://github.com/jayadev133/EIGENVALUES-AND-EIGENVECTORS/assets/150319465/c084a220-47b0-49f6-8b71-7801490f21ed)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
