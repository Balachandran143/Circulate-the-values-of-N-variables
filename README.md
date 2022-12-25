# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
First step is to define function
### Step 2: 
Get l,n inputs from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Finally print the result
### Step 6: 
## Program:
````
#Program to circulate N values.
#Developed by: Balachandran S
#RegisterNumber:22006708
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
````
## Output:
!['output'](/Screenshot%20from%202022-12-25%2018-04-30.png)
## Result:
By this program we able to circulate the values of n - variables
