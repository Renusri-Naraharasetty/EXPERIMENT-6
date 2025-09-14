# EXPERIMENT-6
## AIM:
To write a Python program for checking Palindrome and to write test cases for ir. 

## ALGORITHM

Step 1: Start

Step 2: Get an input from the user by prompting

Step 3: Run a loop form 0 to len/2.

Step 4: Check if the characters are the same both from the start and the end till len/2.

Step 5: If it is, return the result that it is a palindrome.

Step 6: Else, return that it is not a palindrome.

Step 7: Stop. 

## PROGRAM
```python
def is_palindrome(s):
    s = s.replace(" ", "").lower()
    return s == s[::-1]

text = input("Enter a string or number: ")

if is_palindrome(text):
    print(f'"{text}" is a palindrome.')
else:
    print(f'"{text}" is not a palindrome.')

```

## OUTPUT
<img width="1456" height="336" alt="image" src="https://github.com/user-attachments/assets/20a22e29-85a4-4e9d-be7d-78b34d5ba86e" />


## RESULT
Thus the program to check if a string is a palindrome or not is successful.
