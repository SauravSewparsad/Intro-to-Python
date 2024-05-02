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

# Basic Data Structure

Lists
- Python's slicing syntax allows for the extraction of values from lists or strings, with options to add a third value, generate longer lists, and step backward using negative values.
- These operations allow for one-value data extraction.
- This section teaches Python how to modify lists using the append() method, insert() method, remove() method, and pop() method.
- Appends an item to the end of a list, inserts an item at a specific position, and removes items based on their value.
- Pop() removes and returns the last item at the end of the list. A loop with pop() can remove all items from the list.
- Variables store a reference to the list, not a copy, and changes to one variable will be reflected in other variables.
- Copy() method creates a copy of a list, preventing changes from affecting the other. Lists are a powerful data structure in Python, and it's essential to understand their functionality.

Tuples and Sets
- One common use of sets in programming is to remove duplicates from a list, since sets only contain unique values.
- To demonstrate, let's create a list with some duplicate values and de-duplicate it by converting it to a set and back again: myList = ['b', 'c', 'c'] mySet = list(set(myList)).
- Sets can be checked using the membership operator (in), find the length of a set using the length() function, and remove an element from it using the pop() function.
- Tuples, similar to lists but declared with parentheses, are ordered and subscriptable but immutable.
- Despite this, tuples are more efficient due to their less memory usage, making them suitable for large data storage.
- Tuples are useful for returning multiple values from a function in Python.
- They can be separated with commas and unpacked into individual variables using the syntax A, B, C = myTuple.
- Although not as flexible as lists, they offer convenience and elegance.

Dictionaries
- A trailing comma at the end of the last key-value pair is a good practice.
- To access a key-value pair, type the dictionary name followed by the key in square brackets.
- Add a new pair, update an existing pair, and access keys and values using the.keys() and.values() methods.
- A dictionary is a structured structure where values are listed, adding is easy if key exists.
- If key is unknown, if-else statements can be used. Len() function can be used for dictionary length.
- The default dictionary is a solution to simplify code in Python.
- It imports from the collections package and requires specifying the object type to return by default.
- It automatically creates a new default value if a key doesn't exist, simplifying code.
- Unlike regular dictionaries, default dicts offer better data structures than lists and dictionaries.

List Comprehensions
- Python's list comprehension feature distinguishes it from other programming languages by providing a comprehensive listing of numbers, demonstrating its uniqueness.
- A list comprehension is a syntax similar to a for loop, allowing for multiple items in a list.
- It's enclosed in square brackets and can use any variable name, allowing for a for loop in one line and filtering or applying functions to every item.
- List comprehension is a useful tool for working with numbers and strings.
- For example, to create a filtered list of numbers from 0 to 99, we can use the modulus operator to select only those divisible by 10.
- To convert the filtered list into a print statement, we can modify the code to include numbers ending in 0, 1, or 2.
- The "split" function splits a string based on a character or string, splitting it into two sentences or individual words.
- To make the text lowercase, a new function called "cleanWord" uses replace and lower functions to remove periods and convert the string to lowercase.
- This helps keep code concise but not too long or difficult to read.
- Applying the "cleanWord" function to a list comprehension results in a clean list of all words.
- List comprehensions are powerful tools for cleaning text and handling large amounts of data.
- cleanWord = [word for word in sentence.split() for sentence in myString.split('.') ]
- One example is the nested list comprehension, which can group words by the sentence they appeared in.
- This is achieved by breaking the original text into sentences and applying a nested list comprehension to each sentence.
- This results in a two-dimensional structure, grouping clean words by the sentence they appeared in.
- List comprehensions are essential in Python to make code more readable and Pythonic, making users a list comprehension expert.

Dictionaries and Comprehensions
- In Python, dictionary comprehensions can be used to create a new dictionary from an iterable structure, similar to list comprehensions.
- For example, to create a dictionary from a list of tuples, use the syntax "animals = {item[0]: item[1] for item in animalList}".
- To simplify dictionary comprehension in Python, use tuple unpacking instead of "item[0]: item[1]".
- This avoids indexing each tuple element separately and allows for unpacking as many variables as there are elements in each tuple.
- To convert a dictionary back into a list, use the "items" method to return a list of key-value pairs.
- To change the structure of a list, use a list comprehension with the syntax "name_value = [{'name': key, 'value': value} for key, value in animals.items()]" to create a list of dictionary objects with original keys and values.
