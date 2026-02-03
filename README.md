# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library to perform matrix operations.
### Step 2: Read the order of the matrix and matrix elements from the user.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and corresponding eigenvectors.


## Program:
```python
import numpy as np 
A=np.array([[4,2],[2,4]]) 
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1275" height="776" alt="image" src="https://github.com/user-attachments/assets/b5080fe7-c081-408c-a26d-2f3ee2377701" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
