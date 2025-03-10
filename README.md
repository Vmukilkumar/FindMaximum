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
```python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Mukil kumar v 
RegisterNumber: 22008798
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```python
''' 
Program to find the maximum marks using the list method max().
Developed by:Mukil kumar v 
RegisterNumber: 22008798
'''
def max_marks(marks):
    return max(marks)
```
iii) # To find the maximum marks without using builtin functions.
```python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](./img/Screenshot_20230118_112238.png)
![output](./img/Screenshot_20230118_112256.png)
![output](./img/Screenshot_20230118_112307.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.