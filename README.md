# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math

radius = float(input("Enter the radius of the circle: "))

class cse: 
    def mech(self, r): 
        area = math.pi * r * r 
        print("Area of the circle:", area)

obj = cse() 
obj.mech(radius)

```
<img width="396" height="202" alt="Screenshot 2026-06-05 203719" src="https://github.com/user-attachments/assets/a5c7d5e5-7182-46a6-9d0e-634b30d98852" />

## Output

<img width="277" height="80" alt="Screenshot 2026-06-05 203724" src="https://github.com/user-attachments/assets/c09a7408-1c1e-4586-994f-bd8351620b97" />


## Result
Thus To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation. Hence the code has been executed successfully.

------------------------------------------------------------------------------------------------------

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


------------------------------------------------------------------------------------------------

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program

```
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

sorted_by_keys = dict(sorted(data.items())) 
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original dictionary:", data) 
print("Sorted by keys:", sorted_by_keys) 
print("Sorted by values:", sorted_by_values)

```
<img width="367" height="155" alt="Screenshot 2026-06-05 203950" src="https://github.com/user-attachments/assets/7a72238c-34d6-429a-b222-b4ac02245174" />

## Sample Output

<img width="762" height="187" alt="Screenshot 2026-06-05 203957" src="https://github.com/user-attachments/assets/b33a4840-de16-4a1e-b0f0-2c0d40a6bb7d" />


## Result
Thus To write a Python program that sorts a dictionary's: Keys in alphabetical order Values in alphabetical order Hence the code has been executed successfully.


----------------------------------------------------------------------------------------------------

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


-----------------------------------------------------------------------------------------

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program

story.txt  file :

<img width="450" height="282" alt="Screenshot 2026-06-05 205608" src="https://github.com/user-attachments/assets/57b4b7fd-e5a6-46b8-82b3-5d419c0e05e7" />



```
count = 0

with open("story.txt", "r") as file:
    for line in file:
        if line[0] != 'T':
            count += 1

print("Number of lines not starting with 'T':", count)
```
<img width="555" height="197" alt="Screenshot 2026-06-05 205541" src="https://github.com/user-attachments/assets/a067f65b-c53d-4cae-aff3-4b4045c9b1ed" />



## Output
<img width="431" height="45" alt="Screenshot 2026-06-05 205549" src="https://github.com/user-attachments/assets/97087e55-6bc1-4cba-be4d-4e9fea9b55e2" />

## Result
Thus To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'. Hence the code has been executed successfully.









