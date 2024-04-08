# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in function for calculation
### Step 2:
Prepare the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End of the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: KEERTHIVASAN M
#RegisterNumber:212223100021
import numpy as np

# Define the matrix
A = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])

# Find eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Print the results
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues , eigenvectors))

```
## Output:
![image](https://github.com/rdxkeerthi/EIGENVALUES-AND-EIGENVECTORS/assets/147473120/5790b456-0999-4305-942b-4e7868eacbff)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
