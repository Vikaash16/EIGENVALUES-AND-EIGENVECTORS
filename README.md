# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions in the calculations
### Step 2:
Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Vikaash P
#RegisterNumber:212223240180
import numpy as np
matrix=np.array(([4,2],[2,4]))
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
![image](https://github.com/Vikaash16/EIGENVALUES-AND-EIGENVECTORS/assets/139218414/4597d23a-a99c-4f62-8549-d615ccf350cc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
