# Find the maximum of a list of numbers

NAME : Saileshwaran Ganesan

REG NO: 212224230237

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
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark
```



## Output:

![image](https://github.com/user-attachments/assets/92b4b7b9-6a05-49e2-b102-12f149d50b1a)

![image](https://github.com/user-attachments/assets/d55c056c-34ff-44e2-b4bc-1211be552f56)

![image](https://github.com/user-attachments/assets/aadc8aba-a506-48b8-a5a3-121e2d11ac4d)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
