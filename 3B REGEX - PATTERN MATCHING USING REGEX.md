# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that checks if an input string matches the pattern of lowercase letters followed by @ and more lowercase letters using regular expressions.

### ALGORITHM

1. Begin the program.
2. Read a string input from the user and store it in user_input.
3. Define a function find_match(s) that uses re.fullmatch() to check if the string matches the pattern [a-z]+@[a-z]+.
4. If the pattern matches, print "Found a match!", otherwise print "Not matched!".
5. Call the function find_match(user_input) and terminate the program.

### PROGRAM
```
Reg.No: 212223060266
Name: Snega G

import re
def find_match(s):
    print("Found a match!" if re.fullmatch(r'[a-z]+@[a-z]+', s) else "Not matched!")
    
user_input=input()
find_match(user_input)
```
### OUTPUT
<img width="591" height="174" alt="image" src="https://github.com/user-attachments/assets/5cae92ca-5484-4127-b93d-e8edd34dc837" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
