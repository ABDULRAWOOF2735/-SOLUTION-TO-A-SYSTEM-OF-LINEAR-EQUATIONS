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
Developed by:
ABDULRAWOOF
RegisterNumber:212224230003

    import numpy as np
    a = np.array([[1,-3],[3,1]])
    b = np.array([0,10])
    res = np.linalg.solve(a,b)
    print(res)
## Output:
![Screenshot 2025-03-19 131020](https://github.com/user-attachments/assets/4a655e0c-6135-4a33-8e1b-231fc26ebd4d)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

