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
Developed by:Divya R V 
RegisterNumber:23014030 
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:Divya R V 
RegisterNumber:23014030 
'''
def max_marks(marks):
    # write your code here
    a=max(marks)
    return a
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:Divya R V 
RegisterNumber:23014030 
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for number in list1:
        if (number>max):
            max=number
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg)

![Alt text](<Screenshot 2023-11-24 140847.png>)

![Alt text](<3rd output.png>)




## Output:



![Alt text](img/output1.png)

![Alt text](<Screenshot 2023-11-24 140938.png>)

![Alt text](3(ii)output.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.