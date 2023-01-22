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
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        


```


## Output:
![WhatsApp Image 2023-01-22 at 17 39 01](https://user-images.githubusercontent.com/119395610/213915462-e0c2ae82-f0f0-4f06-a6af-3ea043f33f90.jpg)
![WhatsApp Image 2023-01-22 at 17 39 10](https://user-images.githubusercontent.com/119395610/213915605-c0abee9f-ce55-4796-9907-b7326484330b.jpg)
![WhatsApp Image 2023-01-22 at 17 39 21](https://user-images.githubusercontent.com/119395610/213915817-3af0f799-0613-4c3b-af3e-6acac2b25193.jpg)
![WhatsApp Image 2023-01-22 at 17 39 34](https://user-images.githubusercontent.com/119395610/213915631-1f7b35fc-5665-4ff4-a71c-853ab3476ae0.jpg)
![WhatsApp Image 2023-01-22 at 17 39 43](https://user-images.githubusercontent.com/119395610/213915644-65f1175a-6644-4fc6-9ad8-4d210d1f89e1.jpg)
![WhatsApp Image 2023-01-22 at 17 39 54](https://user-images.githubusercontent.com/119395610/213915656-be9529ed-04b3-41df-8954-1fd33bea3831.jpg)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
