# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: s.Ranjani
#RegisterNumber: 25017557
import numpy as np
a = np.array([[1,3],[2,5]])
b = np.array([5,-3])
x = np.linalg.solve(a,b)
print(x)
```

## Output:
<img width="1544" height="356" alt="Screenshot 2025-11-22 140402" src="https://github.com/user-attachments/assets/2fef6971-6847-4133-b202-29c0b9239a2a" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

