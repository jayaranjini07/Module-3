# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM
To write a Python program that matches a string that begins with  "a"  followed by zero or more b's 
---

### ALGORITHM

1. Start
2.Take input from the user and store it in variable i.
3. Use the re.findall() function with the regular expression ^a(b*)$:
4. Check if the result of re.findall() (stored in variable x) is not empty:
   - If it is not empty (if(x):), this means the input string matches the pattern completely.
   - Print "Found a match!"
5. If the result is empty (no match found), print "Not matched!"
6. End

---

### PROGRAM

```pyhton
import re
i=input()
x=re.findall(r"^a(b*)$",i)
if(x):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT

![image](https://github.com/user-attachments/assets/81a68390-f848-455f-b173-230ec7a45507)

### RESULT
Thus the Python program that matches a string that begins with  "a"  followed by zero or more b's was implemented and executed successfully.
