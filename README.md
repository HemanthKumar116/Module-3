# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ''
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

string = input("Enter a string: ")
result = remove(string)
print("Result:", result)
```
## Output
![image](https://github.com/user-attachments/assets/71e39836-6231-4e68-8ed2-ea54c6278d48)

## Result
Thus the program has been successfully executed 


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
s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print("Result: The string is a palindrome.")
else:
    print("Result: The string is not a palindrome.")
```
## Output
![image](https://github.com/user-attachments/assets/a4fc33f6-2c4e-4d59-b406-d54873baa69f)

## Result
Thus the program has been successfully executed 

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Result:", l1)
```
## Output
![image](https://github.com/user-attachments/assets/fb0d876f-760c-4859-9894-747586f3f139)

## Result
Thus the program has been successfully executed 

# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
numbers = [1, 2, 3, 4, 5, 6, 7]

total = sum(numbers)

print("Result:", total)
```
## Output
![image](https://github.com/user-attachments/assets/8b266add-b19b-44fe-b7f6-87e9470f2bdc)

## Result
Thus the program has been successfully executed 

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'c', 'n', 1, 2, 8, 10)

if 'n' in x:
    print("'n' is present in the tuple.")
else:
    print("'n' is not present in the tuple.")

if 8 in x:
    print("8 is present in the tuple.")
else:
    print("8 is not present in the tuple.")
```
## Output
![image](https://github.com/user-attachments/assets/38e06047-61af-4462-956e-e8ef977bc669)

## Result
Thus the program has been successfully executed 
