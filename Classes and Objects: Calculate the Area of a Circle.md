
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
tuple1 = (0, 1)
tuple2 = (2, 3)
joined_tuple = tuple1 + tuple2
print("Joined Tuple:", joined_tuple)
class cse:
    def mech(self, radius):
        pi = 3.14159
        area = pi * (radius ** 2)
        print(f"Area of the circle {area:.2f}")
try:
    r = float(input())
    # Create object and call the method
    obj = cse()
    obj.mech(r)
```

## Output

![image](https://github.com/user-attachments/assets/426821d8-8e22-4241-b29d-6949c7d196e1)

## Result

This program successfully encapsulates the area calculation in a class method and interacts with the user for input.
