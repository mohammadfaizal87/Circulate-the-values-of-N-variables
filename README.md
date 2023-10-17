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
#Program to circulate n number of values
#Developed by: MOHAMMAD FAIZAL S.K
#RegisterNUMBER:23013519
def circulate():
    list1=eval(input())
    n=eval(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](./ex%2002.png)

## Result:
Thus the python program for circulate the values of n variables is executed successfully
