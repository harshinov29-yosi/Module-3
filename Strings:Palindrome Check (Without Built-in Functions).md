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
str1 = 'google'
str2 = str1[::-1]
if str1 == str2:
    print("It is a Palindrome")
else:
    print("It is not a Palindrome")

## Output
<img width="424" height="175" alt="image" src="https://github.com/user-attachments/assets/86fad433-aad9-4829-addf-b1d585e9c85b" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
