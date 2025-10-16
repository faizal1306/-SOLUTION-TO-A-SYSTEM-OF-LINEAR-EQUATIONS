# Ex:1-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Mohamed Faizal M
#RegisterNumber: 24000006
import numpy as np
A = np.array([[1,-3], [3, 1]])
B = np.array([0, 10])
c = np.linalg.solve(A,B)
print(c)
```
## Output:
<img width="1263" height="832" alt="Screenshot 2025-10-16 093959" src="https://github.com/user-attachments/assets/dc21a561-54da-49a6-a16d-131130c1575c" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

