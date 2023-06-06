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
#Program to mark the maximum of marks using the list method sort
#Developed by: BALAMURUGAN B
#RegisterNumber: 212222230016

def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max


```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to mark the maximum of marks using the list method sort
#Developed by: BALAMURUGAN B
#RegisterNumber: 212222230016
def max_marks(marks):
    marks=max(marks)
    return marks


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to mark the maximum of marks using the list method sort
#Developed by: BALAMURUGAN B
#RegisterNumber: 212222230016
def max_marks(list):
    max = list[0]
    for i in list:
        if i >max:
            max = i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![P3A1](https://github.com/BALA291/FindMaximum/assets/120717501/06bf3bd6-db7d-477c-ba73-3d67a8b6d201)
![P3A1O](https://github.com/BALA291/FindMaximum/assets/120717501/b3f6ac50-f350-4405-b905-4238ffbf4ea5)

ii)	# To find the maximum marks using the list method max().
![P3A2](https://github.com/BALA291/FindMaximum/assets/120717501/4611b6b5-98c3-4370-ab49-ce5563a3075d)
![P3A2O](https://github.com/BALA291/FindMaximum/assets/120717501/6b257c85-6ea6-45b6-bab3-c9d504e88922)

iii) # To find the maximum marks without using builtin functions.
![P3A3](https://github.com/BALA291/FindMaximum/assets/120717501/6250a9eb-d433-4451-9838-9052607be429)
![P3A3O](https://github.com/BALA291/FindMaximum/assets/120717501/6a3e7fcd-a34d-4c38-afac-f0ea922a65fc)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using
python programming.
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
