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
Developed by: ABDHULLAH R
RegisterNumber: 23013613
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Developed by: ABDULLAH R
RegisterNumber: 23013613
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Developed by: ABDULLAH R
RegisterNumber: 23013613
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max


```
## Sample Input and Output
![Alt text](<Screenshot 2023-11-28 215912.png>)
![Alt text](<Screenshot 2023-11-28 215921.png>)
![Alt text](<Screenshot 2023-11-28 215929.png>)

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.