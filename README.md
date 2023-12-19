# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(),we can find the solutions.
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: THEJASWINI D
#RegisterNumber: 23008944

import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
B=np.linalg.inv(A)
print(B)

```
## Output:
![image](https://github.com/thejaswinidhanaraj/INVERSE-OF-A-MATRIX/assets/148514511/bac175a5-a80a-4a73-8b98-b62f6e603b21)

## Result:
Thus the inverse of given matrix is successfully solved using python program

