# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program

```py
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range!")
```

## Output
<img width="888" height="50" alt="Screenshot 2025-10-21 094948" src="https://github.com/user-attachments/assets/35e42c65-794d-4b3f-a4ff-fabb3ac55c91" />

## Result
Successfully wrote a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.
