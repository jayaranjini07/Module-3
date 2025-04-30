# Exp.No:3d  
## TUPLES - FIND ALL COMBINATIONS OF TWO TUPLES
---

### AIM  
To Write a python program to find all combination of tuples 1(1,2) tuple2=(5,7).

---

### ALGORITHM

1. Start
2. Define two tuples:
-tuple1 = (1, 4)
-tuple2 = (3, 9)
3. Display both tuples using print().
4. Create an empty list named pairCombi to store the pair combinations.
5. Generate pair combinations (tuple1 × tuple2):
-For each element val1 in tuple1:
  -For each element val2 in tuple2:
    -Append the pair (val1, val2) to pairCombi.
6. Generate reverse pair combinations (tuple2 × tuple1):
-For each element val1 in tuple2:
  -For each element val2 in tuple1:
    -Append the pair (val1, val2) to pairCombi.
7. Print all the combinations stored in pairCombi.
8. End
---

### PROGRAM

```
tuple1 = (1, 4)
tuple2 = (3, 9)
print("First tuple : " + str(tuple1))
print("Second tuple : " + str(tuple2))


pairCombi = [] 
for val1 in tuple1:
    for val2 in tuple2:
        pairCombi.append((val1,val2))

for val1 in tuple2:
    for val2 in tuple1:
        pairCombi.append((val1,val2))


print("All pair Combinations are  : " + str(pairCombi))

```

### OUTPUT

![image](https://github.com/user-attachments/assets/6390b042-22b9-4f26-9a84-4bfa35aadd78)

### RESULT
Thus then python program to find all combination of tuples 1(1,2) tuple2=(5,7) was implemented and executed successfully.
