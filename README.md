# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start
### Step 2:
Input the list of values.
### Step 3: 
Input the number of rotations.
### Step 4: 
Perform a circular shift operation using slicing by rotating the list.
### Step 5:
Output the rotated list.
### Step 6:
End
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)

```
## Output:
![alt text](<Screenshot 2024-03-09 093130.png>)
## Result:
Thus Circulate-the-values-of-N-variables are successfully executed