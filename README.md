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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```



## Output:

![Screenshot 2024-03-24 195433](https://github.com/dhanamoni/FindMaximum/assets/151629757/51df47d7-0857-45c2-aa1b-baf0eff2d526)

![Screenshot 2024-03-24 195451](https://github.com/dhanamoni/FindMaximum/assets/151629757/15bbcb2a-a0c3-47b6-9246-b38ceff7eadf)


![Screenshot 2024-03-24 195505](https://github.com/dhanamoni/FindMaximum/assets/151629757/e633738e-582e-4812-8df1-0160ded891a1)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
