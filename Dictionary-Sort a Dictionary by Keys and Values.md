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
