# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step1 : Import numpy which has built-in function for matrix operation

Step 2: Represent the matrix as a 2D numpy array

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4: End the program

## Program:

```python
import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0, 3]])

evals, evects = np.linalg.eig(A)
print("Eigen values are", evals,"and Eigen Vectors are",evects)
```

## Output:

![image](https://github.com/user-attachments/assets/e142b8c1-2222-4365-a1e7-dec24187ff1f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
