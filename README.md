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
```
Program to mark the maximum of marks using the list method sort
Developed by: TAMILARASAN K S
RegisterNumber: 23000080
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b



```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: TAMILARASAN K S
RegisterNumber: 23000080
'''
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: TAMILARASAN K S
RegisterNumber: 23000080
'''
def max_marks(list1):
    for i in list1:
        if i>94:
            return i



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/KSTamilarasan17/FindMaximum/assets/138849236/5613d2a2-8822-4a86-86ed-fe5457bebbef)
![image](https://github.com/KSTamilarasan17/FindMaximum/assets/138849236/6103be23-372c-4857-887c-1c0d3cea5ed0)
![image](https://github.com/KSTamilarasan17/FindMaximum/assets/138849236/b8fa759c-69df-493a-9e80-301a5666e8b3)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
