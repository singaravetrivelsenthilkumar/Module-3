# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM
REG.No :212222220048
NAME : SINGARAVETRIVEL S
```


import re
a=input()
pattern=r'ab{2,3}'
result=re.search(pattern,a)
if result:
    print("Found a match!")
else:
    print("Not matched!")
 ```   
### OUTPUT
![image](https://github.com/user-attachments/assets/e32f9d76-cb05-49a3-b13e-b856c6f4a37c)


### RESULT
Thus the Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions is successfully verified.
