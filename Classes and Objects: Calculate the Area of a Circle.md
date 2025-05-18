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
```python
import math
class cse:
    def __init__(self, r):
        self.area = math.pi * (r ** 2) 
    def Area(self):
        print("Area of circle:", round(self.area, 2))
r = float(input())
res = cse(r)  
res.Area()
```

## Output
![444169999-a63d6613-b7ca-42ef-a36d-094b3aaffa3b](https://github.com/user-attachments/assets/bfb6caf4-8a23-49a5-8648-3cdbedc01b38)



## Result

Thus,the program has been executed successfully.Thus,the program has been executed successfully.
