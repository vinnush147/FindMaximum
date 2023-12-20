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
Developed by: Vinnush Kumar L S
RegisterNumber: 23012349
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Vinnush Kumar L S
RegisterNumber: 23012349
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Vinnush Kumar L S
RegisterNumber: 23012349
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/vinnush147/FindMaximum/assets/147139234/db6c14d4-e816-4ea1-afe3-61a26138fe7e)
![image](https://github.com/vinnush147/FindMaximum/assets/147139234/8e393baa-1f97-4f3a-96d6-2416cedbc060)
![image](https://github.com/vinnush147/FindMaximum/assets/147139234/7f36638c-2689-4fe6-bfb3-351305880054)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
