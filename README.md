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
''' 
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

### i)  To find the maximum of marks using the list method sort.
![image](https://github.com/etjabajasphin/FindMaximum/assets/147139744/c6305f3e-abc5-49e3-bc4c-3037887f0d38)

### ii) To find the maximum marks using the list method max().
![image](https://github.com/etjabajasphin/FindMaximum/assets/147139744/7844d782-0516-4f57-a9fc-ce05917c695a)

### iii) To find the maximum marks without using builtin functions.
![image](https://github.com/etjabajasphin/FindMaximum/assets/147139744/f1626f25-a6f0-4789-8a08-076a807cd8af)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
