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
a=list(map(int,input().split()))
a.sort()
print(a[-1])




```
## OUTPUT:
<img width="448" height="145" alt="image" src="https://github.com/user-attachments/assets/3f62b3de-8d0a-4fb0-ac66-1faa6d2ce121" />


ii)	# To find the maximum marks using the list method max().
```
a=list(map(int,input().split()))
print(max(a))





```
## OUTPUT:
<img width="456" height="135" alt="image" src="https://github.com/user-attachments/assets/db31b230-2886-4672-b840-b88c00ade29c" />


iii) # To find the maximum marks without using builtin functions.
```
a=list(map(int,input().split()))
max=a[0]
for i in a:
    if(i>max):
        max=i
print(max)




```
## OUTPUT:
<img width="518" height="143" alt="image" src="https://github.com/user-attachments/assets/4d006d4b-7378-4a5c-9b80-b18a182422f5" />



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
