# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:

Assume the keyword to run the program
### Step 2:

Assing the value of the first variable
### step 3:

Get the value from the user for the number of rotation
### Step 4:

Using the slicing concept rotate the list
### Step 5:

using the slicing concept rotate the list withthe denote of the first variable
### Step 6:

print the values of the first variable

## Program:
```
Developed by: Thiyagarajan A
Ref no:212222240110
def circulate():
    list=eval(input())
    n=int(input())
    result=list[n:]+list[:n]
    print("After circulating the values are:",result)
```
## Output:
![circulate2](https://user-images.githubusercontent.com/118707693/228889828-0a0966fc-a39f-4d97-84f7-f19167b9e6b4.png)

## Result:
The result was excuted sucessfully.
