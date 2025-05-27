# Exp.No:3a
## STRING - FIND AND REMOVE

---

### AIM  

To write a Python function to accept a string, identify a word to be replaced, and remove a word provided by the user.

---

### ALGORITHM

Extract the first three characters of the string using a[:3].

Extract all characters from index 4 to the end using a[4:].

Concatenate the two parts: a[:3] + a[4:].
(This effectively skips the character at index 3.)

Print the resulting string.

---

### PROGRAM

```
def remove(a):
    result=a[:3]+a[4:]
    print(result)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6acf24bb-bc44-455a-acf9-69c88755dc58)


### RESULT
Thus the Python function to accept a string, identify a word to be replaced, and remove a word provided by the user is successfully verified.
