# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Imports the NumPy library and allows you to reference it using the shorthand "np".

### Step 2:  Defines a 2x2 matrix "A" using a nested list.

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: Prints the eigenvalues and eigenvectors in a formatted string.  

## Program:
```
import numpy as np
A=([4,2],[2,4])
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values Vectors))
```


## Output:
![Alt text](<Screenshot 2023-12-01 130142.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
