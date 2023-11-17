# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input())

### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatenation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```py
#Program to circulate N values.
#Developed by:MOHAMMAD FAIZAL SK
#RegisterNumber:23013519
def circulate():
  list1=eval(input())
  n=eval(input())
  result=list1[n:]+list1[:n]
  print("After circulating the values are:",result)

```

## Output:
![output](https://github.com/mohammadfaizal87/Circulate-the-values-of-N-variables/assets/147139206/99ebd064-3675-42e0-b9ff-880964544dec)


## Result:
Thus the python program for circulate the values of n variables is executed successfully.
