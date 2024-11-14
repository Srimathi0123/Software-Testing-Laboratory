# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:16/08/24                                                                            
### REGISTER NUMBER : 212221040162

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        if start < 0 or end < 0:
            print("Both values must be positive.")
            display()
            return

        while start <= end:
            print(start, end=' ')
            start += 1
        print()  # For a new line after printing the numbers
    else:
        print("Enter a valid positive number.")
        display()

display()
```
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while start < end:
            print(start)
            start += 1
    else:
        print("Enter a valid positive number.")
        display()

display()
```
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")
        switch()

switch()

```
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")
    print() 

iterate()
```

### Output:

![image](https://github.com/user-attachments/assets/6f7eca5e-7ff1-426b-a7f5-aafcd5ef8e03)
![image](https://github.com/user-attachments/assets/6c1be841-a3e0-44db-8c9c-4fbd801f6a8d)
![image](https://github.com/user-attachments/assets/06e16b40-6c51-4537-b191-edabca2a5614)
![image](https://github.com/user-attachments/assets/ef64f0d9-aa32-4ead-b23c-7e5dbf2a90c4)
![image](https://github.com/user-attachments/assets/7498a428-23af-49b2-aa4d-824d4afe89ba)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


