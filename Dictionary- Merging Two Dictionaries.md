## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```py
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    return merged

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

result = merge(dict1, dict2)
print("Merged dictionary:", result)
```
## Output
<img width="918" height="57" alt="Screenshot 2025-10-21 091816" src="https://github.com/user-attachments/assets/6e46e6a1-564f-463d-9ee1-224daf4274ba" />

## Result
Successfully wrote a Python program that merges **two dictionaries** and combines their key-value pairs.
