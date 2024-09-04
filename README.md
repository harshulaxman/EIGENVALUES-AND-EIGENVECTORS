# DATE:
# EXP-4: EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step1 :
we have imported numpy which is needed.

Step 2:
we have created a matrix using np.array with different values in it.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
finally,print the values of the eigen values and eigen vectors.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Harsshitha lakshmanan 
#RegisterNumber:212223230075
import numpy as np
a=np.array([[4,2],[2,4]])
val,vect=np.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vect);
```
## Output:

![image](https://github.com/user-attachments/assets/a06c4257-d7bd-4f01-b9f3-5463a8a8794f)

![image](https://github.com/user-attachments/assets/c9722d20-aa7c-414f-85d2-81cfb03a3f5a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
