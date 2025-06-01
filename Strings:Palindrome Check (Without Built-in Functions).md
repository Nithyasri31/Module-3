# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
s=input() 
palindrome(s)

```


## Output
![444904693-cf27a708-0b7d-47f2-8ac0-7fcbd82e7c56](https://github.com/user-attachments/assets/1e9bb54d-1ab5-4c60-9b57-fecfa80fc5b6)

## Result

Thus the program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed successfully.
