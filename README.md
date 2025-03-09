
**Resources that I have used** : django documentation, geekforgeeks, vscode IDE, and git, GitHub

# Task - Custom Classes in Python

An instance of the Rectangle class requires length:int and width:int to be initialized.

We can iterate over an instance of the Rectangle class 

When an instance of the Rectangle class is iterated over, we first get its length in the format: {'length': <VALUE_OF_LENGTH>} followed by the width {width: <VALUE_OF_WIDTH>}

**Explanation of code and logic implementation.**

1: I have defined a class Rectangle to store length and width.

2: __init__ method to Initializes the class with length and width stored in a dictionary.

3: __iter__ method to Makes the class usable in loops.

4: __next__ method to Handles looping through the rectangle’s properties (length and width).

5: __repr__ method to Formats the rectangle object for display when printed.

Example as - Rectangle(50, 75) creates a rectangle, and looping through it prints {'length': 50}, {'width': 75}.


