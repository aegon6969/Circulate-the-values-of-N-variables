# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function
### Step 2:  
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4:
print the output
## Program:
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are:",a)


## Output:
![OUTPUT](/n%20values.png)
## Result:
This program is used to circulate the values
