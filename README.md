# Experiment-7
## AIM : Write a python program for sorting and inspect for failures. 
## Algorithm:
Start the program.
2. Get the number of elements from user
3. Get the elements to be sorted
4. Traverse the array and sort the elements one by one
5. Print the sorted array
6. Stop the program. 
# Program:
```
n = int(input("Enter the number of elements: "))  
arr = []  
try:  
    for i in range(n):  
        a = float(input("Enter the element: "))  
        arr.append(a)  
    for i in range(n):  
        for j in range(n - i - 1):  
            if arr[j] > arr[j + 1]:  
                temp = arr[j]  
                arr[j] = arr[j + 1]  
                arr[j + 1] = temp  
    print("The array after sorting: ", end="")  
    for i in range(n):  
        print(arr[i], end=" ")  
except ValueError:  
    print("Enter a valid number")
```
# Output
<img width="600" height="215" alt="image" src="https://github.com/user-attachments/assets/ffef904f-f88d-4036-b706-7fa2c0828e19" />

<img width="646" height="197" alt="image" src="https://github.com/user-attachments/assets/caf599d0-7bca-4cc1-a0c4-dacd27f5863a" />

<img width="528" height="146" alt="image" src="https://github.com/user-attachments/assets/f3be6e7e-8f59-4b33-b6ec-c694ea706c6a" />



# Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully
