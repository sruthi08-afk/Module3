# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---
 
### AIM  
To write a Python program that matches a string that has an 'a' followed by anything, ending in 'b'. 
--- 

### ALGORITHM

1.Begin the program.  
2.Take user input as a string (s).
3.Define the regex pattern r"a.*b$": a → Ensures the string contains 'a'.
                                     .* → Matches any sequence of characters (including none).
                                     b$ → Ensures the string ends with 'b'.
4.Use the re.search() function to check if s matches the pattern.
5.If a match is found, print "Found a match!".
6.Else, print "Not matched!".
7.Terminate the program.

---

### PROGRAM

```
#Reg.NO 212223020026
#Name SRUTHI.K
import re
s=input()
pat="[^a]+[b$]"
if re.search(pat,s):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/7adb6d66-fdc9-4b1b-a747-c36539a3b804)


### RESULT
Thus a Python program that matches a string that has an 'a' followed by anything, ending in 'b' is executed successfully. 
