# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by:SRIVATSAN V
RegisterNumber:23000970
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SRIVATSAN V
RegisterNumber: 23000970
'''
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SRIVATSAN V
RegisterNumber: 23000970
'''
def max_marks(list1):
    a=0
    
    for i in list1:
        if i>a:
            a=i
    return a


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-26 103612](https://github.com/Srivatsan0405/FindMaximum/assets/139841630/c19f7f02-b691-4c21-814c-81655a2ec65c)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
