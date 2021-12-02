# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
 Get the value from the user for the number of rotation
### Step 2: 
Using the slicing concept rotate the list
### Step 3: 
Print the output.
  
## Program:
```def circulate():
    list1=[10,20,30,40,50,60]
    n=int(input())
    list1=list1[n:]+list1[:n]
    print("After circulating the values are:",list1)
```

## Output:
![values2](./values2.png)

## Result:
