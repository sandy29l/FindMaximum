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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Santhosh L
RegisterNumber: 212222100046

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Santhosh L
RegisterNumber: 212222100046

def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Santhosh L
RegisterNumber: 212222100046
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Sample Input and Output
## Output:
![Screenshot (16)](https://github.com/sandy29l/FindMaximum/assets/123359969/0a2a49f7-2d6b-4bd6-b6aa-9176ffaa8115)
![Screenshot (17)](https://github.com/sandy29l/FindMaximum/assets/123359969/abd7ddea-f322-4031-9a21-b23c04f6c8d2)
![Screenshot (18)](https://github.com/sandy29l/FindMaximum/assets/123359969/dab71b75-a68a-4449-8e8b-15247e718c87)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
