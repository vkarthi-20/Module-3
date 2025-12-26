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
result = []
for item in items:
    if not re.search(r'e', item):
        result.append(item)
print(result)
```
## Output
<img width="918" height="199" alt="530164720-9523e953-b8db-4b13-861e-a40a746e343d" src="https://github.com/user-attachments/assets/6ad15c51-ab12-48ad-b477-f4a0a3d0ad7a" />


## Result
We got the successful output
