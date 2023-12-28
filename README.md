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

### i) To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: Jerowin Geo J A
RegisterNumber: 23013644
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

### ii) To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Jerowin Geo J A
RegisterNumber: 23013644
'''
def max_marks(marks):
    large=max(marks)
    return large
```

### iii) To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Jerowin Geo J A
RegisterNumber: 23013644
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

### i) To find the maximum of marks using the list method sort.
![image](https://github.com/JerowinGeo/FindMaximum/assets/147139744/4db08a1b-0643-41ac-9a0f-45817b512664)

### ii) To find the maximum marks using the list method max().
![image](https://github.com/JerowinGeo/FindMaximum/assets/147139744/6182334e-05c3-4d6a-b4ff-97539745aa4c)

### iii) To find the maximum marks without using builtin functions.
![image](https://github.com/JerowinGeo/FindMaximum/assets/147139744/b0444463-f8c6-46cb-88df-a148982509e2)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
