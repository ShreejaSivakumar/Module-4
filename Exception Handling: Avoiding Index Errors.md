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

```
list1 = [1, 2, 3, 4]

try: 
    print(list1[5]) 
except IndexError: 
    print("You're out of list range")
```

<img width="513" height="217" alt="Screenshot 2026-06-05 204048" src="https://github.com/user-attachments/assets/5bdf5fa1-97e9-4297-ba29-14d29e793e80" />

## Output

<img width="472" height="126" alt="Screenshot 2026-06-05 204053" src="https://github.com/user-attachments/assets/4e07a992-cd27-4070-aa0d-3a3f84a74b88" />


## Result
Thus To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list. Hence the code has been executed successfully.
