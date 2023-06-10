# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 :
Import the numpy module to use the built-in functions for calculations.

### Step 2:
Prepare the lists from each equations and assign in np.array().

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:

```

#Program to find the eigen values and eigen vectors.
#Developed by: M.Harini
#RegisterNumber:212222240035
import numpy as np
A=np.array(([-2,2,-3],[2,1,-6],[-1,-2,0]))
evalues,evector=np.linalg.eig(A)
print ("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))


```


## Output:

![image](https://github.com/Harinimuthu17/EIGENVALUES-AND-EIGENVECTORS/assets/130278614/cb141c40-8ec2-4d83-8983-cb8bf2bee678)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
