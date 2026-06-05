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
