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
```python
with open("story.txt", "r") as file:
    count = 0  
    for line in file:
        if not line.startswith('T'): 
            count += 1  

print("Number of lines that do not start with 'T':", count)

```

## Output

![444172922-9050496e-ffab-4506-8dfb-5cca2898dbb4](https://github.com/user-attachments/assets/4cfc4cd2-06d1-4f7f-bd4d-fab9bb142d1a)



## Result

Thus,the program has been executed successfully.
