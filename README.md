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
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091
'''
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091
'''
def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
           maximum=i
    return maximum    


```

## Output:
![python ex 3a(1)](https://github.com/mrnaviz/FindMaximum/assets/123350791/1cf4ea27-edc9-4854-a480-bdbbf0a1d6ad)
![python 3a(2)](https://github.com/mrnaviz/FindMaximum/assets/123350791/35d40c47-dbac-4614-8a54-6995ca0a30ad)
![python 3a(3)](https://github.com/mrnaviz/FindMaximum/assets/123350791/97c4de02-b905-4941-918e-2e07c1e5d065)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
