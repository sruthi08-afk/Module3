# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 3 AND ITS SUM

---

### AIM  
To write a Python program to create a tuple containing all multiples of 3 up to a given number  **N**nd the print sum of the elements of the list.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_3` with values starting from `3` up to `N - 1`, stepping by `3`.  
4. Return the tuple `multiples_of_3`.
5. Calculate the sum of the elements 
6. Print the resulting tuple.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K
a=int(input())
b=[i for i in range(3,a) if i%3==0]
print(tuple(b))
print("Sum is",sum(b))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/7aef5a37-a9fe-4a8a-9125-532cf1e10251)


### RESULT
Thus a Python program to create a tuple containing all multiples of 3 up to a given number  **N**nd the print sum of the elements of the list is executed successfully.
