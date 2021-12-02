# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built in function for calculation.
### Step 2: 
Prepare lists from each linear equations and assign in np.array()
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
Print the val format.
### Step 5: 
End the program.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: S.Manoj 
#RegisterNumber:21500146
import math
x=[10,6]
y=[4,2]
val=math.sqrt(((x[0]-x[1])**2)+((y[0]-y[1])**2))
print('{:.2f}'.format(val))
```
  
### OUTPUT:
![Distance between two points](./outputpic.png)


### RESULT:
Thus a python program to find the distance two 2 points is obtained.
