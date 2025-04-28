
# Exp.No:3b  
## REGEX - FIND SEQUENCES

### AIM  

To write a Python program to find sequences of Upper case letters joined with a '@'.

### ALGORITHM

1. Begin the program.  
2. Input a string from the user.
3. Use regex to check if the string matches the pattern:
   One or more capital letters [A-Z]+
   Followed by one or more @ symbols @+
   Followed by one or more capital letters [A-Z]+
   And ends there ($).
4. If match found, print "Found a match!".
5. Else, print "Not matched!".
6. Terminate the program.

### PROGRAM

```
import re
s = input()
if re.search(r'[A-Z]+@+[A-Z]+$',s):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT

![image](https://github.com/user-attachments/assets/22f8d4bb-9ae2-419b-8e6c-559b4a9424f9)

### RESULT

Thus the Python program to find sequences of Upper case letters joined with a '@' was successfully founded.
