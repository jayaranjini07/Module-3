# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To Write a python function Vowcount() that accepts a string and should count and display the occurrence of words starting with a vowel in the given string.

---

### ALGORITHM

1. Start
2. Input: A string s (sentence or phrase).
3. Split the string s into a list of words using split() and update s.
4. Initialize a counter c to 0 for counting words that start with vowels.
5. For each word i in the list s:
-Check if the first character of the word (i[0]) is a vowel (i.e., in "AEIOUaeiou").
 -If yes, print the word.
 -Increment the counter c by 1.
6. After checking all words, print the total count: "No. of Words starts with vowels are", c.
7. End

---

### PROGRAM

```
def  Vowcount(s):
    s=s.split()
    c=0
    for i in s:
        if i[0] in "AEIOUaeiou":
            print(i)
            c+=1
    print("No. of Words starts with vowels are",c)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/f2aac746-288e-4055-a821-79e11ba7012d)

### RESULT
Thus the python function Vowcount() that accepts a string and should count and display the occurrence of words starting with a vowel in the given string was implemented and executed successfully.
