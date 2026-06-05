## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = {'a': 1, 'b': 2, 'c': 3} 
dict2 = {'b': 20, 'd': 4}

def merge(): 
    merged = {**dict1, **dict2} 
    print(merged)

merge()
```
<img width="311" height="172" alt="Screenshot 2026-06-05 203846" src="https://github.com/user-attachments/assets/2af6ef47-0de8-4549-8732-c6a40fe7b302" />


## Output
<img width="287" height="75" alt="Screenshot 2026-06-05 203849" src="https://github.com/user-attachments/assets/eefbc551-0e3e-4047-8f52-f27a5efb60d4" />


## Result
Thus To write a Python program that merges two dictionaries and combines their key-value pairs. Hence the code has been executed successfully.
