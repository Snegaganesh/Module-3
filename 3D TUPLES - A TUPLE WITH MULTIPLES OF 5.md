# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 3


### AIM  
To write a Python program to create a tuple containing all multiples of 3 up to a given number **N**.


### ALGORITHM
1. Begin the program.
2. Read an integer input `N` from the user.
3. Define a function `create_tuple_and_sum(N)` that:
4. Print the tuple `multiples_of_3` and the sum `total_sum`.
5. Terminate the program.

### PROGRAM
```
Reg.No: 212223060266
Name: Snega G

def create_tuple_and_sum(N):
    multiples_of_3 = tuple(i for i in range(3, N, 3))
    total_sum = sum(multiples_of_3)
    print(multiples_of_3)
    print(f"Sum is {total_sum}")
N = int(input())
create_tuple_and_sum(N)
```

### OUTPUT
<img width="803" height="211" alt="image" src="https://github.com/user-attachments/assets/23a4cc21-2e83-4554-bb9c-5d673ddbed55" />

### RESULT
Thus a Python program to create a tuple containing all multiples of 3 up to a given number N was executed and implemented successfully.
