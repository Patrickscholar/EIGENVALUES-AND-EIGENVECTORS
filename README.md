# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: Import the NumPy library
Use the statement import numpy as np to include the NumPy library in the program.
## Step 2: Define the NumPy array
Create a 2x2 matrix 
 using np.array() with the desired values.
## Step 3: Compute eigenvalues and eigenvectors
Use the function np.linalg.eig(A) to calculate the eigenvalues and eigenvectors of the matrix 
. This function returns two results: the first is the eigenvalues, and the second is the eigenvectors.
## Step 4: Print the output
Display the eigenvalues and eigenvectors using a formatted print statement to show the results clearly.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: V PATRICK ALEX EMMANUEL
#RegisterNumber: 212224240110
import numpy as np
A = np.array([[2, 2],
              [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues,"and","Eigen Vectors are",eigenvectors)
```
## Output:
<img width="943" alt="Screenshot 2025-05-22 at 10 52 11 AM" src="https://github.com/user-attachments/assets/2f4bd141-39a0-427e-b634-c0eba6c7d984" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
