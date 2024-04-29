# Python
This module introduces the basics of Python programming, a powerful and easy-to-learn language with efficient high-level data structures and object-oriented approach. Its elegant syntax, dynamic typing, and interpreted nature make it ideal for scripting and rapid application development. The module covers notable Python features, allowing readers to read and write Python modules and programs.

-------------------------------------------------------

# Week 1: Python Syntax

# Introduction

How computers work
- Computers store files and data in a grid-like memory, with each file having a file name, size, and a pointer.
- The computer accesses the file's contents by following the pointer, which represents the location of the file in the memory.
- A computer program interacts with the computer's memory by creating variables, which are mini files with names and addresses pointing to specific locations.
- For example, a program like A = 2, B = 3, C = A + B calculates A plus B.
- In Python, a list of numbers, A, is assigned to a variable B, which points to the same memory location as A.
- Any changes to A will affect B, making memory assignment crucial in programming as it involves data input, retrieval, and manipulation.
- Understanding computer execution and memory location is crucial for complex programs.
- It's essential to understand how variables are assigned, how modifications affect each other, and how data is stored in memory.

Zen of python
- Python, a three-decade-old language, has gained popularity due to its elegant, modern syntax.
- Unlike JavaScript, Python is suitable for complex systems and beginners.
- Its true potential lies in situations with fewer complexities, as demonstrated by its hidden mission statement "import this."
- To access the Python command prompt, open a terminal and type "Python". Once opened, there are three greater-than symbols indicating that the prompt is ready to accept a line of Python code.
- The "import" command is used to import a module, with "this" being the module name. This will print out a document.

Writing python Programs
- We will now write our first Python program, which can be done using any text editor. Visual Studio Code, Sublime, PyCharm, and Notepad++ (for Windows users) are some recommended options.
- Comments in programming provide information about a line of code, such as "Hello, World!", and should be saved before proceeding to the terminal or command prompt.
- To access a stored file, use the "cd" command, type the file directory, and run the "hello.py" program. The text "Hello, World!" will be printed to the screen.

Jupyter Notebook
- In this course, we'll be utilizing Jupyter Notebooks for the majority of our programming work. You may be wondering why we're using it and what the benefits are, especially after the installation process.
- Project Jupyter is a non-profit organization that creates Python tools for programming and data science, including the popular Jupyter Notebook web application, which allows users to write and execute Python programs in their browser.
- The webpage can be opened manually by copying and pasting URLs. Files ending in ipynb are notebook files created using IPython, popular in data science for easy presentation and sharing of charts and graphs.
- Create a Python 3 notebook by clicking "new" and selecting "Python 3". These notebooks are useful for experimenting, creating code-based reports, and teaching Python efficiently, and can be exported in various formats.
- Jupyter Notebooks allow users to create new cells by holding down the shift key and pressing enter multiple times, delete cells by clicking outside the cell, enter Python code, add cells, and use keyboard shortcuts A or B. Markdown cells can add human-readable text, titles, and math equations.
- To modify a file, use an IDE like Visual Studio Code, where you can edit, run, and perform similar actions as in a web browser.

-----------------------------------------------------------------

# Getting started with python

Variables and Types
- A variable is the basic unit of a program, assigned a value using an equal sign.
- In Jupyter Notebooks, cells can be run using Shift + Enter, and variable names can include upper and lower case letters.
- Python offers various types of variables, including integers, floats, complex numbers, strings, and booleans.
- The plus sign concatenates strings and numbers, but cannot add them. Error messages provide useful information.

Data structures
- In Python, data structures store values in a single variable, including lists and sets.
- Lists can contain any data type, while sets contain unique elements and are declared using curly braces.
- Sets and tuples store large amounts of data efficiently in memory, while dictionaries are collections of key-value pairs.
- Sets' order isn't important, tuples cannot be modified, and keys are used for access.

Operators
- In Python, operators are instructions that perform operations on variables and values, such as arithmetic operators for mathematical calculations.
- Examples include addition, multiplication, and exponent operators, which manipulate data and perform actions on variables.
- The forward slash operator performs division, returning a floating-point value.
- The modulus operator provides the remainder after division, like 20 divided by 6.
- Strings can be manipulated using addition, multiplication, or addition, with addition working only with two strings and multiplication working with either a string or a number.
- Python offers a range of operators, including comparison, logical, identity, and membership operators.
- Comparison operators evaluate two variables or values and produce a Boolean result, such as true or false.
- Logical operators, like "and," "or," and "not," operate on Boolean values, returning true if both operands are true or false if at least one operand is true.
- Membership operators, like "in" and "not in," check if a value is present in a sequence.
- These operators enable various operations and comparisons, and their usage can be combined and used in various ways.

Control flow
- The if statement is a key control flow in programming, executing code only if a certain condition is met.
- In Python, it's used like this: "a = True, if a: print It is true." Indenting further adds code, while adding an else statement executes code if condition is false.
- In Python, indentation is crucial for program structure.
- For loops iterate over a list or iterable object, while while loops continue until a condition is false.
- The item in the for loop represents the current item, while the while loop loops until the condition is false, ensuring the loop continues indefinitely.

Functions
- A function is like a machine that takes inputs and produces outputs, just like a toaster that takes in bread and produces toast. Even if the input is not bread, the toaster can still apply its toasting function.
- In Python, functions are defined using the "def" keyword, with the function name and arguments in parentheses.
- The function body contains code, and the "return" keyword specifies output. Functions can take arguments and may or may not return a value, with "None" representing the absence of value.

Classes and objects
-  To create a complete kitchen with various abilities like toasting, baking, microwaving, dishwashing, and coffee making, each with its own settings, programmers invented a class in Python.
-  This tool helps label and organize related collections of functions and attributes, reducing the need for extensive, unmanageable code with numerous variables.
-  In programming, classes are defined using an uppercase letter and include functions and attributes like legs, name, and bark.
-  An initialization function is created, called every instance of the class, and a variable called "self" is used to access the class.
-  For example, a Dog with four legs, "Rover" name, and "speak" function can be created.
-  To use a class, create a new instance of the Dog class by calling "dog" with necessary variables.
-  Multiple dogs can be created, each accessing its functions and attributes.
-  The speak function takes "self" as the first variable, representing the class instance.

-------------------------------------------------------------------

# Basic data types

Ints and floats
- Python automatically returns a float for non-whole numbers, and adding a float to an int or multiplying with both also returns a float.
- To convert 256.0 to an int, use the int class, which is a built-in class in Python. C
- Casting is a straightforward conversion, but it can be tricky when dealing with values like 8.9. To round a float to the nearest int, use the round function.
- Floats are approximations, causing rounding errors due to limited memory.
- However, using the round function can mitigate this issue.
- Be cautious when using floats, especially in significant decimal places, especially when handling money.

Alternative Number types
- The int class in Python can convert a string to an integer, and convert a second argument to base 10.
- However, the first argument must always be a string, as non-numeric characters in the string may be valid in different bases, like "1ab" in base 16.
- Python's decimal module addresses floating point errors in floats, allowing for more accurate decimal calculations.
- To use it, import the decimal class and use the getcontext function, which returns a context object with global settings for decimal usage.
- The decimal class allows instantiation of decimal objects with number values, such as 0.3333 divided by 3.
- However, it may lead to floating point errors if the float is passed as a string.
- It's not always necessary to use the decimal class over floats, but rounding appropriately and dealing with small or large numbers is recommended.

Booleans
- Python's boolean casting is crucial for understanding its use in if statements or loops.
- It allows for the evaluation of integers, strings, and data structures.
- Booleans are typically used in if statements or loops, and understanding their values is essential for evaluating them.
- However, there are multiple ways to evaluate a boolean, so logic must be careful.
- For example, evaluating a list based on weather and umbrellas requires adding parentheses or using an "and" statement to get the correct logic.

Strings
- Python is a powerful tool for analyzing and constructing strings, with slicing being a particularly useful method for extracting data and presenting it to the user.
- For example, to get the first character of a string, use name[0].
-  For the first seven characters, use name[0:7], excluding the space after "name." Shorthand syntax is also available. For all characters from index 11 to the end, use name[11:].
-  Python offers string creation methods like string concatenation and f-strings, which insert variables or expressions, round numbers, and perform formatting, similar to the format function from Python versions before 3.6.
- Python offers a feature for creating multi-line strings using triple quotes, which can be escaped with a backslash. It has numerous string functions and methods.

Bytes
- Python uses the bytes object to store data as a random sequence of ones and zeros, which is rarely modified directly.
- It is commonly used for streaming files or transmitting texts without knowing the encoding, and Python knows its type when loading the data.
- To create a bytes object in Python, specify the type (utf-8) and use the decode function to convert it back into a string.
- Bytes objects are immutable, but can be modified using slice notation or the int library.
- Bytes can be converted from hexadecimal values to bytes, and can be used to find, detect, use, and modify data.

-----------------------------------------------------------------
