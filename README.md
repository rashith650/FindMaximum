### Date : 
# Ex-6 : Find the maximum of a list of numbers
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
Program to find the square root for the given number(newton's method) using function.</br>
Developed by: Mohamed Rashith</br>
RegisterNumber : 24001082</br></br>
i)	# To find the maximum of marks using the list method sort.</br>
```Python
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().</br>
```Python
def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.</br>
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:

![6 1](https://github.com/user-attachments/assets/4cf1ec22-f2a3-4599-a3e1-17d6eaa0dff6)
![6 2](https://github.com/user-attachments/assets/72530e19-d00e-4872-8e57-74d98e1481d3)
![6 3](https://github.com/user-attachments/assets/5d69eccc-807e-4a69-b33b-8a1db86f3b31)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
