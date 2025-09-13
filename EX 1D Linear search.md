# EX 1D Linear search
## DATE:09-07-2025
## AIM:
To write a python program for a search function with parameter list name and the value to be searched on the given list of float values.



## Algorithm
1. Input the list of numbers and the search target n.
2. Iterate through the list, comparing each element with n.
3. If a match is found, return 1 to indicate the number is found.
4. If the end of the list is reached without a match, return -1 indicating the number is not found.
5. Print the result based on whether the number was found or not.

## Program:
```
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: GANESH PRABHU J
Register Number: 212223220023
```
```py
def search(List, n):
    for i in List:
        if i==n:
            return i
    return -1
n=int(input())
list1=[float(input()) for _ in range(n)]
List=tuple(list1)
target=float(input())
sol=search(List,target)
if sol==-1:
    print(f"{target} Not Found")
else:
    print(f"{sol} Found")

```

## Output:

![image](https://github.com/user-attachments/assets/57ed2350-23db-410b-9f04-a215704e8883)


## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
