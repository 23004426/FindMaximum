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
#Developed by: Tirupathi Jayadeep
#RegisterNumber: 23004426
def max_marks(marks):
    large=max(marks)
    return large
    



```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: Tirupathi Jayadeep
#RegisterNumber:23004426 
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin functions.
#Developed by: Tirupathi Jayadeep
#RegisterNumber:23004426  
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i> max:
           max = i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
1.![Screenshot 2023-12-03 150333](https://github.com/23004426/FindMaximum/assets/144979327/7fbe25ad-9cff-4987-88d4-8e6867eb4c33)
2.![Screenshot 2023-12-03 150353](https://github.com/23004426/FindMaximum/assets/144979327/c8323c2f-fa92-48e7-b47e-53fea54a83a4)
3.![Screenshot 2023-12-03 150353](https://github.com/23004426/FindMaximum/assets/144979327/65f75cb1-a369-4fdf-af7d-3262a7900eb8)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
