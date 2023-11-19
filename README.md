# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
Get the n values from the users
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the output
### Step 6: 
End the program
```
## Program:
#Program to circulate N values.
#Developed by: GUTTHA KEERTHANA
#RegisterNumber: 23012783
def circulate():
    list1 = eval(input())
    n = int(input())
    result =list1[n:] + list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![circulatenvariables](https://github.com/keerthanaguttha/Circulate-the-values-of-N-variables/assets/145742927/dc6843cc-8edd-49d8-8421-0016ddcb59da)


## Result:
Thus the circulate the two variables are sucessfully executed
