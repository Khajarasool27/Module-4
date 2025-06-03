
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
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```
## Output

![image](https://github.com/user-attachments/assets/62b88713-9a12-4d5e-9663-7c5e5f0e557e)

## Result

The program correctly merges the dictionaries and handles key collisions as expected.


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
d = {3: 323, 2: 56, 4: 24, 6: 18, 5: 12, 1: 2}
sorted_items = sorted(d.items(), key=lambda item: item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
```

## Sample Output

![image](https://github.com/user-attachments/assets/6b805508-048e-446a-8957-dea99de7778d)

## Result

The program successfully sorts the dictionary by both keys and values.


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
list1 = [10, 20, 30]
try:
    print("Accessing list1[5]:", list1[5]) 
except IndexError:
    print("You're out of list range")
```
## Output

![image](https://github.com/user-attachments/assets/f243ed2c-72dc-468a-9204-2fa2f06b1596)

## Result

This program correctly demonstrates exception handling for out-of-range list access.

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
```
def returnSum(myDict):
    final = sum(myDict.values())
    return final
dict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :", returnSum(dict))
```

## Output

![image](https://github.com/user-attachments/assets/b9f91c63-6fa0-433f-b3a0-e8c517da45d6)


## Result

The program reads the file safely, trims leading spaces to handle indentation, and correctly counts lines that don't start with 'T'
