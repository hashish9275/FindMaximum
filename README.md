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
Program to mark the maximum of marks using the list method sort
Developed by: K R HASHISH VIDYA SAGAR
RegisterNumber: 212222230047 

def max_marks(marks):
    marks.sort()
    large = max(marks)
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: K R HASHISH VIDYA SAGAR
RegisterNumber: 212222230047
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: K R HASHISH VIDYA SAGAR
RegisterNumber: 212222230047
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

i)

![py xp 3a i](https://user-images.githubusercontent.com/118707521/235308912-05b915a2-02fa-477e-80cb-e8fe614e39f4.png)

ii)

![py xp 3a ii](https://user-images.githubusercontent.com/118707521/235308941-41e87811-6d75-40d2-aa08-96c419b40f68.png)

iii)

![py xp 3a iii](https://user-images.githubusercontent.com/118707521/235308958-5cf49571-881d-4b4b-8cf1-f2320b41482d.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
