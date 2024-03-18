# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
def circulate():
    m=eval(input())
    n=int(input())
    m=m[n:]+m[:n]
    print('After circulating the values are:',m)
```
## Output:
![Screenshot 2024-03-18 192641](https://github.com/Vinishofficial/Circulate-the-values-of-N-variables/assets/146931793/6cd187eb-abc1-45a6-b407-0b0d07d92c4e)


## Result:
The output for circulate the values of n variables is successfull.
