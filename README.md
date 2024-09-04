# Ex-2 : Circulate-the-values-of-N-variables
## Date:
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
# Developed by: Suriya Pravin M
# Register no: 212223230223
def circulate():
    global lst,n
    n = n % len(lst)
    rotated_list = lst[n:] + lst[:n]
    print(f"After circulating the values are: {rotated_list}")
lst=list(eval(input()))
n = int(input())
```

## Output:
![EXP-2_ CR Circulate n variables_ Attempt review _ SEC](https://github.com/user-attachments/assets/d2666751-f04b-485b-8018-9d9f9c5211e5)


## Result:
The output for circulate the values of n variables is successfull.
