Classes and Objects in Python: Calculate the Area of a Circle
🎯 Aim
To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

🧠 Algorithm
Get user input: Take the radius of the circle as input from the user.
Define the class: Create a class named cse.
Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
Area = pi *r^2
Execute the program: Create an object of the class and call the method with the radius value.
🧾 Program
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
Output
image

Result
This program successfully encapsulates the area calculation in a class method and interacts with the user for input.

Dictionary Operations in Python: Merging Two Dictionaries
🎯 Aim
To write a Python program that merges two dictionaries and combines their key-value pairs.

🧠 Algorithm
Define two dictionaries dict1 and dict2 with some key-value pairs.
Define a function merge() that merges the two dictionaries using the ** unpacking operator.
The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
Call the merge() function and print the merged dictionary.
🧾 Program
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
Output
image

Result
The program correctly merges the dictionaries and handles key collisions as expected.

🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values
This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values
🎯 Aim
To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order
🧠 Algorithm
Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.
🧪Program
d = {3: 323, 2: 56, 4: 24, 6: 18, 5: 12, 1: 2}
sorted_items = sorted(d.items(), key=lambda item: item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
Sample Output
image

Result
The program successfully sorts the dictionary by both keys and values.

Exception Handling in Python: Avoiding Index Errors
🎯 Aim
To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

🧠 Algorithm
Define a list list1 with some integer elements.
Use a try-except block:
In the try block, attempt to access an index that is out of range (e.g., list1[5]).
In the except block, catch the error and print a custom message "You're out of list range".
Print the result based on whether the index access succeeds or fails.
🧾 Program
list1 = [10, 20, 30]
try:
    print("Accessing list1[5]:", list1[5]) 
except IndexError:
    print("You're out of list range")
Output
image

Result
This program correctly demonstrates exception handling for out-of-range list access.

File Handling in Python: Count Lines Not Starting with 'T'
🎯 Aim
To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.

🧠 Algorithm
Open the file story.txt in read mode.
Initialize a counter count to zero.
Iterate through each line of the file:
Check if the first character of the line is not 'T'.
If the line does not start with 'T', increment the count by 1.
After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.
🧾 Program
def returnSum(myDict):
    final = sum(myDict.values())
    return final
dict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :", returnSum(dict))
Output
image

Result
The program reads the file safely, trims leading spaces to handle indentation, and correctly counts lines that don't start with 'T'
