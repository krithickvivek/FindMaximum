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

i) To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Krithick Vivekananda
RegisterNumber: 23009445
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max


```

ii)	To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Krithick Vivekananda
RegisterNumber: 23009445
'''
def max_marks(marks):
    max1=max(marks)
    return max1



```

iii) To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Krithick Vivekananda
RegisterNumber: 23009445
'''
def max_marks(list1):
    max1=0
    for i in list1:
        if i>max1:
            max1=i
    return max1
    
    


```

## Output:

1) To find the maximum of marks using the list method sort.

![sort](maxsort.png)

2) To find the maximum marks using the list method max().

![max](maxmax.png)

3)  To find the maximum marks without using builtin functions.

![nobuiltin](maxnobuiltin.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.