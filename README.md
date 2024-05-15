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
-------------------------------------------------------------

# Basic Control Flow

If and Else
- This text introduces conditional statements in Python, a crucial tool for writing most programs.
- It introduces a new statement, the switch statement, which evaluates a series of values and runs code instructions corresponding to the first true value found.
- Python is superior to other programming languages, so it is not necessary to learn the switch statement.
- The text then discusses a classic problem in programming: iterating through numbers one to 100 and printing "Fizz" if divisible by three, "Buzz" if divisible by five, "FizzBuzz" if divisible by 15, and the number itself if none of the conditions are met.
- The code is rewritten using the elif statement, which stands for "else if."
- If else statements can be lengthy, so ternary operators are useful for one-liner evaluations.
- They evaluate a Boolean condition and return true or false values. Python programmers aim for clean, readable code, but must be cautious with ternary operators.

While
- When running code with a while loop, use the break statement to exit early and move on to the next line, or the continue statement to skip over certain lines within the loop and jump back to the top for the next iteration.
- Use a continue statement within an if statement to prevent code from running under certain conditions or to rearrange code for readable purposes, understanding when to use them is crucial.

For
- The for loop is a common Python loop that declares a new variable, like "item," to hold the value of each element in a list.
- It can be used with statements like pass, continue, and break, and can be used to find prime numbers or to stop the loop early.
- Understanding these loop statements helps maintain a clean and Pythonic code.
-------------------------------------------------------------

# WEEK 2 PYTHON

# Basic functions

anatomy of a function
- Functions are named and parameterized using def statements. A simple function, performOperation, takes two numbers and an operation (sum or multiply) as input and returns the result, if sum is used.
- To simplify the process of specifying the operation parameter as "sum" repeatedly, we can assign a default value using name parameters or keyword arguments.
-  Named parameters
    + Remove the "operation equals multiply" part to get five, or assign your own value using "multiply" as the third parameter.
    + Add a "message" keyword argument to a function, specifying a default message to be printed when called, and pass the message before or after the operation.
- args
   + In Python, keyword arguments must precede positional arguments, with the order of the first two being crucial. However, keyword arguments can be arranged in any order.
   + Optional arguments in Python have a functional limitation of allowing multiple variables.
   + To allow users to pass in any number of variables, use the asterisk symbol before the argument name.
   + This works only for positional arguments, not keyword arguments, preventing "unexpected keyword argument" errors.
- kwargs
   + Kwags is a method for handling keyword arguments, which are stored as a dictionary instead of a tuple, as they have keys, values, and can be passed in any order.
   + To make the performOperation function more flexible, import the math library and rewrite it to use args as the default argument.
   + The function can perform desired operations by passing in the appropriate arguments, such as adding numbers to get the desired result.

# Variables and Scope
- function scope
   + The "locals" function in Python allows access to all variables within a function without asterisks, using the method *args and **kwargs to print out arguments.

- locals()
   + Modify the function definition to execute num1, num2, and multiplication, defaulting to addition.
   + Use the locals function in Python to print the output, which contains a dictionary of variables.
   + Locals variables are accessible only within the function, avoiding errors when referencing outside its scope.
   + In Python, there are two types of variables: local variables, which are defined inside the function, and global variables, which are defined outside the function in the main code block. Thankfully, Python comes with a handy built-in function called globals that enables us to retrieve all of these variables.

- globals()
   + Python's pre-built variables are useful for working with classes and packages, while Jupyter Notebooks use variables to manage data.
   + The scope of variables in a line of code determines which can be accessed, classified as global or local variable scope.

- Global and Local Scope
   + Two functions, one with variables A and B and the other with variables C and B, will be created, each with its own local variable scope and global scope access.
   + The global scope allows variables like varA to be printed in both functions, but if they're defined in function one's local scope, an error occurs.
   + Redefining a message in function one's local scope allows both local and global values to be printed.
   + Similarly, declaring a function within another function only allows it to be called within it, causing a syntax error.

# Functions As Variables
Variables as Functions
- Variables and functions both have names and data associated with them. However, for functions, this data includes information about required parameters and the lines of instruction to be executed. In Python, a function is represented as an object.

Viewing Function Data With  __code__
- The "code" attribute of Python function objects can be used to confirm that functions are just variables in Python. Print the variable names and the byte object of all the lines of instruction in a function using this attribute. However, this is not something you would typically need to use. 

Text Processing in Python
- The text outlines two text processing operations and a function that can lowercase, remove punctuation, new lines, and words with three or less characters.
- These operations can be arranged in a list, allowing for flexibility in the order and selection of text processing functions, making it a useful tool for business processes.

Lambda Functions
- Lambda functions are a way to define small functions without assigning a variable name, like 5 or 2 + 3.
- They can be used to pass a function as an argument to another Python function, like a sorted function.
- Lambda functions are concise and convenient for writing small functions needed in code.
- They are useful when passing a function as an argument to another Python function, such as a sorted function.
---------------------------------------------------------------

# Classes and Objects Fundamentals 

Anatomy of class
- Instance Attributes
   + The concept of classes can be confusing, but an example is the dog class.
   + It has two attribute attributes, name and legs.
   + However, the value of the legs attribute is hardcoded and cannot be directly accessed.
   + This raises questions about whether having four legs is an inherent property of being a dog or if three-legged dogs can be created as well.

- Static Attributes
   + Change the handling of the legs attribute in the class to define it as a static variable outside of the constructor, ensuring each instance has the same value.
   + These static variables are commonly used for holding constants or business logic.
   + To prevent modification, programmers add an underscore before the variable name and use a getter method to retrieve the value, either without passing in the self attribute or with self included.

Instance and Static Methods
- One of your favorite things to do in Python may be string parsing. To demonstrate, create a class called Word Set that contains a set of words. 
1. Start with an empty set and add to it by passing in big blocks of text, punctuation and all. 
2. Add text using the method add text, which first calls the method clean text to remove the punctuation and make everything lowercase. 
3. Then use the split function to turn the sentence into a list of words, which can be added to the set. 
4. Finally, print the set of words.
- The clean text method is a static method, unlike add text, which is an instance method.
- Static variables like replace puncs can be added, but cannot be referred to with instance methods.

Inheritance
- Class Inheritance
  + In Python programming, one class can inherit all methods and attributes of another, known as the parent class.
  + This inheritance occurs automatically when the child class is created.
  + For example, a dog class can be inherited into a chihuahua class, which can be created using the parent dog class's methods and attributes.
  + This allows for the creation of a new instance.

- Extending Built-in Classes
   + Python's built-in classes can be extended to create unique lists.
   + By instantiating a list as "list", we can override the append function and check if an item is already in the list.
   + However, self.append is not recommended as it can cause infinite recursion or an endless loop.
   + Instead, we use the "super" function to call the original append function in the parent class.
   + To test the new class, create a new instance of the unique list and append items to it.
   + The "super" function is also used in the constructor to add a new attribute to a child class instance.
   + However, this overwrites the parent class's constructor, which may have essential initialization requirements.
   + To avoid this, use "super" again and ensure the parent constructor is called first before adding the new property.
   + Class extensions are an elegant and powerful tool for resolving coding issues.
-------------------------------------------------------------------------

# Error Handling Fundamentals

Handling Errors and Exceptions
- Python's syntax varies between errors and exceptions, with exceptions determined during runtime and retryable, and errors cannot be retried.
- However, they all function similarly, with the base exception class providing useful properties like halting code execution and providing information about why and how it was halted.
- For example, the division by zero error is an example of an exception that extends the base exception class.
- The stack trace, which shows the original location of the function call and where the error was triggered, is a crucial tool for debugging Python programs.
- Expanding the stack trace further by creating a function called "callCauseError" can further expand the trace, making it even longer.
- In large programs with multiple files, stack traces can become extensive, making it essential to interpret them effectively.
- Exceptions, seemingly daunting due to small code mistakes, are actually classes. They can be caught using a try/except statement, allowing us to obtain an instance of the raised exception.
- Try/Except
   + To handle exceptions, add 1/0 and use the except exception as e.
   + This will catch the exception and prevent it from being raised.
   + Exceptions are not to worry about but require careful consideration.
   + Handling them correctly is like a secondary layer of code, ensuring error-free or beautiful errors.

Managing and Handling Exceptions
- Exceptions are not to be feared, but they need to be managed.
- The Try / Except statement can be used to catch and return an exception without a stack trace.
- This pattern can be used to print something without requiring the ase instance, indicating an error.

  + Finally
    - The finally statement is a useful tool in programming, as it ensures that a function always executes and prints out, regardless of what happens inside the Try/Excuse block.
    - This is often used to time the execution time of a function.
    - To use this, import the time class and create a timer using the start time and seconds.
    - In the finally statement, use the time.time variable to display the current time and seconds. Time.sleep can pause execution for a specified number of seconds, allowing for fast execution.
    - This try-finally pattern maintains code cleanliness and compactness, allowing for cleanup or logging after a statement completes.
   + Catching Exceptions by Type
      - The text explains how to catch exceptions in Python, focusing on zero division and type errors.
      - It suggests adding another except statement and chaining them together.
      - The order of these except statements matters, with Python trying the first one.
      - The general exception should be placed down, followed by more specific ones.
      - This is useful for handling complex exceptions, such as HTTP request-response handling, where multiple except statements are in a row.
      - To simplify this process, it is suggested to copy and paste these blocks into multiple functions, allowing for easier handling and catching in a single function.
   + Custom Decorators
      - Custom decorators can be used to handle exceptions in Java.
      - Create a new function called handleException, passing a function as an argument and defining an inner function called wrapper.
      - Execute the function and paste exceptions into the wrapper function.
      - Create a handleException decorator and place it on a causeError function, returning one over zero.
      - This handle exception can be reused for another function.
   + Raising Exceptions
      - Raising exceptions in Java is a powerful technique that can be achieved by using the handle exception decorator.
      - A function called raiseError raise Exception can be created, which raises or throws a new exception when it is reached.
      - This can be used to except input except the number zero, add an argument, and print n if it equals zero.
      - However, when using the handleException function on a function that takes arguments, there are no arguments when called, causing an error when rerun.
      - Combining handle exceptions with custom exceptions can make it easier to raise exceptions in Java.

Working With Custom Exceptions
- Custom exceptions is an easy one. In fact, you already know how to do this, class CustomException extends Exception:pass. Now you have written a custom exception.
- The pass statement is used to create a new CustomException class without defining anything.
- The name of the class contains key information that helps debug apps or inform users about errors.
- A function can be written to raise a new CustomException, def causeError:raise CustomException, and then call the function.
- The custom message is then passed into the new class, which is then printed out. Custom exceptions are lightweight classes with minimal special attributes, but may have useful attributes for organizing and presenting error information.
- For instance, a web server may have an HttpException class and specific HttpException classes that extend it.

  + Adding Attributes
    - This text outlines the creation of an HTTP exception with a static status code and message attribute, and how to format the string passed to the parent exception.
    - The HttpException class is defined as an extension of the Exception, with a status code of None and a message of None.
    - The constructor is overridden by the child class, which is defined as a 404 status code and a message of Resource not found.
    - A ServerError class is created, with a status code of 500 and a message of "This server messed up!".
    - The function raiseServerError is then called, and the exception message is formatted with the status code and message.
---------------------------------------------------------------

# Threads and Processes Fundamentals

Fundamentals of Threads and Processes
- Computers operate on memory and file storage, which are segmented and controlled by the operating system.
- Long-term memory is used when a file is saved and loaded, while short-term memory is used when declaring variables in a program.
- The operating system allocates memory to each process, preventing them from accessing each other's memory.
- A process can have multiple threads and execute code in parallel, allowing for more efficient computations.
- This chapter will focus on computing in parallel, inside different threads and processes.

Multithreading
- In programming, threads and processes are often used to handle large-scale tasks like fetching data from a remote server.
- To create a function that calculates the square of a number, import the threading and time modules.
- Create a function called longSquare, which takes a long time to complete.
- For example, to calculate the square of a few numbers, create two threads: t1 and t2. Pass in two keyword arguments: target and args.
- Start both threads with the start function and join them with the join function.
- This runs in about half the time it would take to run them one at a time.
- However, the return value of the function is not available in the threads.
- To get the output, create a results dictionary and modify the function to pass in the results dictionary.
- Pass in the results, add them to the dictionary, print them, and then print the results.
- To keep things organized, create a list called threads, plural, and call the function t.start for t in threads.
- Finally, print the results. This is faster than waiting one at a time and allows for more complex tasks.

Multiprocessing
- Multi-processing and Python can be used to create two separate Python processes running independently on a machine.
- To start, stop, and manage these processes, a module called multiprocessing can be used.
- The module can be installed with pip install multiprocess, which has all the same functions and is used exactly as multiprocess but does not have the bug with pickiness about where the function is defined.
- To use multiprocess and the time module, replace the thread class with the process class and call it p1 and p2.
- This should work as expected, but there are no results.
- Processes do not share memory, and they get a copy of the dictionary in their own separate memory space.
- To print the computed value from within the function itself, print one and a four instead of returning or saving it in the results.
- If you add 10 processes to the mix, use the same pattern as before with the threads.
- Processes are equal to a list, and new lines are not where they were expected.
- In summary, multi-processing and Python can be used to create two separate Python processes running independently on a machine.
- The multiprocess module can be used to manage these processes, but it may not be as efficient as the threading module.
------------------------------------------------------------4

# Fundamentals of Working with Files 

Opening, Reading and Writing
- Reading files
   + Python programmers often need to produce tangible files for management purposes, such as attaching to emails or opening in Excel.
   + Working with files in Python is not as simple as double-clicking an icon on a desktop, as it involves working directly with the operating system.
   + It is important to manage whether the program is reading the file's contents or intending to make changes.
   + This is because two applications can make changes to the same file simultaneously, causing problems.
   + To do this, use the open function with the file name and the string R as arguments.

- Writing Files
   + To access the text inside a file, use the readline function, which reads the file one line at a time.
   + This file object contains a bookmark of read lines. Another option is readlines, plural, which retrieves all unread lines from the file and converts them into a list of strings.
   + To print the file contents, use the for line in f.readlines, print line. Note that the lines are double-spaced due to new line characters and the print statement.
   + To fix this, use the strip function on each line to remove leading or trailing white space, including new lines. This method is more visually appealing than ugly.
- Appending Files
   + In Python, writing files is an efficient operation that uses a W for write instead of an R.
   + The output.txt file is created when the write function is run. However, when opening the output file, it doesn't exist.
   + Python tries to make file writing more efficient by putting all data in a buffer and only writing to the file when the buffer gets full or when the file is closed.
   + To close the file, use f.close and then run the write function. When reopening the file, it doesn't print a new line character between the lines, so adding a new line character is necessary.

CVS
- Reading
   + The text describes a CSV file called 10_02_us.csv, derived from a dataset from geonames.org.
   + The file contains zip codes in the US, city or town information, and latitude and longitude of its location.
   + To read the file, we open it in read mode and pass it to a new csv.reader.
   + This reader is an iterable CSV reader class, but it does not parse the file correctly due to tab-separated values. To fix this, we pass a spac slash T as a delimiter argument, backslash T.
   + This will split the values and parse comma-separated values correctly.
   + The first row printed is the header, and the CSV reader has a function called next to skip over the header.
   + The reader has an internal bookmark that keeps track of where you are.
   + If you want to use header data, you can use the dict reader, csv.DictReader, which uses the same delimiter.
   + This header is used as the keys in each dictionary in the list, making it a useful data format in Python.
- Filtering Data
   + Convert data from reader object to list object, storing prime numbers between 2 and 99,999.
   + Filter prime locations by filtering rows by int data postal code in primes.
   + Limit search to Massachusetts and row state code to MA. Print out the length of data, as prime locations can start with 0.
   + The search should be limited to Massachusetts and row state code equals MA.

JSON
- Loading JSON
   + In this text, we discuss the concept of JSON files and their format, specifically JSON strings.
   + It is important to note that JSON is not Python, but rather a string. To convert a string into a dictionary, we need to import the JSON module, import json, and use the json.loads method to pass in the string, jsonString.
   + It is important to note that this method is called loads plural, not loads singular.
   + Adding a trailing comma to a JSON string can cause a JSON decode error, which is common when working with JSON from untrustworthy sources.
   + To avoid this, we need to import the JSON module and JSONDecodeError from json. This is the same as reading JSON, but with a different approach.

- Dumping JSON
   + Use the json.dumps method for formatting a valid Python dictionary as a JSON string.
   + This method is dumps plural and typically doesn't require exception handling. However, there's one exception where an exception could be thrown.

- Custom JSON Decoders
   + Create an animal class and modify the dictionary to use it.
   + Replace the apple with an aardvark, bear, or cat. The JSON module doesn't know how to handle this Animal class.
   + To fix this, override the default JSON encoder with a new one.
   + Import the JSONEncoder class and create a new AnimalEncoder class.
   + Override the default method, def default self and o, which is the object to be decoded into JSON.
   + This ensures the correct JSON representation of the Animal class.
-------------------------------------------------------

# Week 3
# Project Planning

Finding Inspiration
- The initial challenge in programming is determining what the program should accomplish, similar to the writer's block faced by aspiring authors.
- To overcome this, various sources of inspiration can be shared to fuel your next Python project.
- Start with hobbies, such as attending concerts or organizing your photo collection.
- Consider automating mundane tasks in your workplace by writing a Python script to transfer data or generate reports.
- Reflect on your daily routine at home and consider tasks that could be streamlined through automation.
- For example, develop an application that sends a daily email digest, compiling all necessary information in one convenient place.
- This project serves as the guiding example throughout the course.
- Add new ideas to your list as you go about your day, keeping them ready to be explored.
- This will help you find exciting projects to explore and overcome your writer's block.

User Stories
- The planning process for a daily email digest generator in Python involves determining specific details through user stories.
- These brief, informal stories should focus on the user's goal and motivation, rather than the application itself.
- They should follow the format "As a [user/role], I want [goal] so that [reason/benefit]."
- Additional user stories can be written to elaborate on specific aspects, such as reading inspirational quotes or weather forecasts.
- It is crucial to avoid overloading the application with every possible feature, keeping the initial scope manageable.
- Ideas for additional features can be kept separately in a backlog. Focusing on the user's goals and reasons is essential, rather than specific interface details or implementation methods.
- Writing your own set of user stories is valuable for project development.

Use Cases
- User stories and use cases are planning tools for applications, with use cases containing a title, an actor, and a scenario describing how a goal is achieved.
- They complement each other, with user stories focusing on the who, what, and why of a task or goal, and use cases covering the who, what, and how of achieving that goal.
- The choice between using user stories alone or combining them depends on the complexity of the project and the user's personal working style.

Project Requirements
- Traditional requirements are essential for formally defining the capabilities and limitations of an application.
- Functional requirements outline what the application should or should not do, such as generating inspirational quotes, retrieving weather forecasts, Twitter trends, and Wikipedia articles, and formatting them into an email.
- These requirements are high-level, omitting specific details like forecast duration or temperature unit.
- Non-functional requirements focus on maintainability, reliability, and usability, such as having a configurable GUI for admin interaction, extensible content types, and resilience to content errors.
- These requirements help initiate the first iteration of the application, making it a good time for individuals to write their own set of functional and non-functional requirements.

Architecture
- Traditional requirements are essential for formally defining the capabilities and limitations of an application.
- Functional requirements outline what the application should or should not do, such as generating inspirational quotes, retrieving weather forecasts, Twitter trends, and Wikipedia articles, and formatting them into an email.
- These requirements are high-level, omitting specific details like forecast duration or temperature unit.
- Non-functional requirements focus on maintainability, reliability, and usability, such as having a configurable GUI for admin interaction, extensible content types, and resilience to content errors.
- These requirements help initiate the first iteration of the application, making it a good time for individuals to write their own set of functional and non-functional requirements.

Stub Code
- The program has been designed using three Python modules: dd_content.py, dd_email.py, and dd_gui.py.
- The dd_email.py module contains the daily digest email class, with placeholder methods and a pass statement for execution.
- The dd_content module includes independent functions for retrieving random quotes, weather forecasts, Twitter trends, and Wikipedia articles, allowing for future expansion with additional content sources.
- The dd_gui module handles the graphical user interface for the email digest administrator, using the TKinter module.
- Import statements for TKinter are included, and the if name equals main section is filled with standard code to build and run the GUI.
- The stub code provides structure for implementation, allowing for separate development of the email class, independent content functions, and the GUI.
----------------------------------------------
# Content Retrieval

Daily Inspirational Quotes
- The "dd_content.py" module will implement four functions, including the "get_random_quote" function.
- The source of random quotes is determined, and a personal list of inspirational quotes is chosen for simplicity.
- The CSV format is chosen for simplicity.
- The "get_random_quote" function is implemented in the "dd_content.py" file, taking a named parameter for the quotes file location and creating a list of dictionaries using list comprehension.
- A default quote is defined in case the file fails to load.
- The random module's "choice" function is used to select a random quote from the list, which is returned as a dictionary object.
- Testing code is added to demonstrate quote generation functionality, with the "get_random_quote" function called without an input argument and the returned quote printed.
- The script will display the generated quotes, with the first quote retrieved from the "quotes.csv" file and the second quote being the default quote by Eric Idle.

Weather Forecasting with OpenWeatherMap
- The text outlines the implementation of the get_random_quote function and the subsequent content function, get_weather_forecast. The weather forecast data needs to be current, so it cannot be stored in a local CSV file. Instead, it must be sourced from the internet using Python web-scraping libraries or online sources like openweathermap.org. OpenWeatherMap offers various callable APIs for accessing current and forecast weather information, which require registration with the service and obtaining an API key.
- The 5-Day / 3-Hour Forecast is the most suitable option, providing weather data in three-hour intervals. The API documentation provides examples of different ways to request the forecast based on the city's name, ID number, geographic coordinates, or even a ZIP code. The geographic coordinates option requires latitude and longitude values to specify the desired forecast location.
- For the initial version of the application, the forecast should be used as the only recipient of the email digest. The default format for the returned data is JSON, but only select few relevant fields. The Python code that calls and utilizes the forecast API includes three new modules: the request module from the urllib package, the JSON module to parse the response, and the datetime module to format and store the timestamp for each forecast period.
- The get_weather_forecast function retrieves weather forecasts based on coordinates, with a default location near Cape Canaveral, Florida, if no coordinates are provided. The script includes an OpenWeatherMap API key, formats a URL using the API key and coordinates, and uses the request module to retrieve the JSON response from the API.
- A simplified forecast dictionary is created instead of returning the entire dictionary obtained from the load function, including desired information such as the city, country, and a list to store forecast data for future time periods. A for loop is used to iterate through the first nine three-hour forecast periods, gathering relevant information for the next 24 hours.
- The get_weather_forecast function returns the newly constructed forecast dictionary if everything goes smoothly, but if an error occurs, the except block will execute, printing the exception and the function will return none. The function is tested using three cases: calling the function without arguments, providing coordinates for Austin, Texas, and defining invalid coordinates. The output shows the forecast for the default location (Cape Canaveral), followed by the forecast for Austin, Texas, and an error message when invalid coordinates are used, confirming the function's expected behavior.

Trending Social Media Content (Twitter)
- The development of the DD content module required access to current Twitter trends. To do so, developers needed to register a Twitter account, request API access, and obtain an API key. However, the authentication process was complex, so they searched for a Python library that could handle it. They found Twitter on pypi.org, but instead of searching through over 3,000 Python projects related to Twitter, they turned to Google for solutions.
- Tweepy is a popular, regularly updated Python library with the required capabilities for this project. Its documentation reveals an API method called "trends_place," which retrieves current trends based on a location's unique identifier called WOEID (Where On Earth Identifier). To use Tweepy, install it on your computer, import the Tweepy module, and define a function called "get_twitter_trends" with an optional parameter for the WOEID value.
- The function returns the current trends as a list of dictionaries, each containing information about a trend. For testing purposes, three test cases were created: the first case without arguments, which retrieved and printed trends for the default region, the second case passing a WOEID corresponding to London, and the last case passing an invalid WOEID, resulting in an exception and the function returning None.
- When the DD content module was run in a terminal, the output displayed the top Twitter trends for the United States and London, but an error message appeared for the invalid WOEID case because the function couldn't retrieve trends for that location.

Importing Articles
- The fourth content retrieval function aims to fetch a random Wikipedia article.
- The search for a Wikipedia API documentation led to finding the desired information.
- The REST API allows access to their content. The get button is clicked, followed by the try it out button.
- The desired return format is selected, with options for a random page title, full page HTML, or a summary of key points.
- The execute button is clicked. The request URL field displays the URL for obtaining a random summary, and the response body in JSON format includes fields such as page title, thumbnail images, full page URL, and an extract field.
- The code for the function to retrieve Wikipedia articles and parse the response shares similarities with the previous implementation of the weather forecast function.
- The updated get Wikipedia article function uses the request module's URL open function to access the URL for a random page summary.
- The JSON module's load function is used for parsing the response, extracting specific information from the response.
- The final test case is added to display the retrieved page title, URL, and extract.
---------------------------------------------------

# Digest Email

Writing and Formatting Email Messages
- The Daily Digest email Python module implements the format message method to format various content into the email's body.
- It is possible to include both plaintext and HTML formats in a single email message using Python's MIMEMultipart class. HTML is the more commonly used format for emails today.
- The daily digest email class is implemented using an init constructor method that initializes an instance variable as a dictionary to store four types of content, each with a Boolean flag indicating if it should be included.
- The latest content is retrieved using functions from the DD content module.
- The format message method formats the Plaintext version of the message, setting the text variable as a formatted string with a header including the current date.
- Stylistic elements like asterisks and tildes are added to make the Plaintext section header stand out.
- The method checks if each content type should be included and adds the section headers and formatted text accordingly.
- For generating HTML content, HTML strings are concatenated to the HTML variable using HTML tags and angle brackets to define the display format like a webpage.
- IF statements determine whether each content type should be included.
- An HTML footer is added towards the end of the format message function, and the text and HTML message are returned as a dictionary.
- The test code generates a new message, prints the Plaintext and HTML content to the console, and saves them in text and HTML files for further inspection.

Sending an Email
- Python's 'email' library is used to manage email messages, with the 'email.message' module being the main tool for creating daily digest emails.
- The module consists of a class called 'Email Message', which is used to combine components like subject line, recipient list, and message content. However, setting up and running an email server locally is not recommended.
- Many online email services offer an SMTP server for external email clients and applications.
- Google changed its security policy in May 2022, making it less secure, so Gmail is no longer recommended.
- Instead, Outlook email addresses can be used. Microsoft's support page provides information on the server name, port, and encryption method for connecting to the Outlook SMTP server.
- The send email function creates a new email message object with various fields, generates the message body using the format message method, configures the email to use plain text using the set content method, and includes the HTML version using the ad alternative method.
- The send email method establishes a secure connection to the SMTP server using TLS encryption.
- To test the code, a call to the send email method is added at the end of the script.
- The email is sent to a recipient's inbox, displaying both plain text and HTML versions.
- This makes the daily digest email compatible with a wider range of email clients and settings.

Task Scheduling
- The original outline for a daily digest email class was successfully implemented, with the format message and send email methods added.
- However, the final task was to implement the ability to send the daily digest at a specific time every day.
- To do this, a method called schedule time was added in the GUI, allowing the administrator to set the desired sending time for the email.
- The library "schedule" was chosen for its easy-to-use interface for scheduling tasks to repeat at specific intervals or times of day.
- However, the scheduler lacks the capability to operate in the background, meaning that if a task is scheduled to send an email in the future, the program will remain idle until that task is completed, preventing the administrator from interacting with the program.
- A workaround for running the scheduler as a separate thread can be found in the documentation.
- In the implementation, a new class called the scheduler was created, incorporating the scheduled time method from the GUI class and the send time field from the email class.
- By inheriting from Python's threading module's thread class, the scheduler can run independently from the main thread.
- When it is time to send another email digest, the scheduler calls the email class's send email method, while the GUI uses the scheduler's scheduled time method to determine the send time.
- The implementation involves creating a new module and class for the daily digest scheduler, using the schedule API for scheduling tasks, and ensuring continuous execution of pending tasks until the stop flag is triggered. The run method ensures continuous execution of pending tasks until the stop flag is triggered.
- To test the DD scheduler script, a test email was sent at 11:20, and a new daily digest was received at the specified time.
- The new scheduler class works by scheduling a test email to be sent at the specified time, and the program remains active by sleeping the main thread for 60 seconds while the scheduler waits to send the email.
--------------------------------------------

# Building a Graphical User Interface (GUI)

GUI Design Planning
- The author has completed the implementation of four content generation functions, an email class for formatting and sending the daily digest, and a scheduler.
- However, they also included a non-functional requirement to create a graphical user interface (GUI) for the admin's use.
- To create a GUI, the author breaks down the project into smaller parts, dividing each task into separate boxes and arranging elements within them.
- They later reorganized these boxes as subsections to create the overall GUI layout.
- The purpose of the GUI is to provide users with options to customize their digest email, including content sources, managing recipients, scheduling sending time, and configuring sender credentials.
- To start designing the GUI, the author breaks it down into smaller parts, focusing on tasks like adding and removing recipients.
- Check buttons were used to turn on or off binary choices, and a section header was added to make it clear what check buttons were related to.
- For managing recipients' lists, a list box was used, and a button called "Remove Selected" was added to remove selected recipients.
- A simple single-line text entry field was used for adding recipients, and the "Add Recipient" button was rearranged to be at the top.
- A section header was added for recipient configuration controls.
- Spin boxes were used to decide when to send the digest, and text entry fields were used for setting up sender credentials.
- To recognize configuration changes, the author suggests creating a GUI that automatically updates the program's variables whenever a change is made in the fields.
- This would prevent unintended actions and ensure that the admin can lock in new configuration settings.

Exploring Python Tkinter GUI
- The "dd GUI" is a Python GUI module that consists of 250 lines and is designed to interact with daily digest email and scheduler modules.
- The "route" parameter in the initialization method of the daily digest class corresponds to the TKinter window where the GUI is built.
- The code adds a title, header label, and defines font styles to the window using the TKinter API.
- The code follows a pattern to create different parts of the GUI, such as adding and removing recipients, scheduling delivery time, configuring email content, updating sender credentials, and controlling settings updates.
- All variables are instantiated within the initialization method to simplify field initialization.
- The code is organized into two sections: creating TKinter widgets, positioning them within the frame, and using TKinter's grid geometry manager for widget placement.
- Four callback methods are associated with buttons in the GUI: "add recipients," "remove selected recipients," and "update settings."A bonus button was added to manually send an email digest.
- The final method, "shutdown," stops the scheduler thread before closing the GUI window.
- The "if name is main" section spawns the GUI as the top-level script.
- The module provides all necessary controls for the project, including adding/removing recipients, scheduling send time, selecting content, and updating settings.
-------------------------------

# Design Iteration

Iterative enhancements
- Congratulations on completing the initial scope of the daily digest project! It's important to continue improving the application by implementing tasks such as saving configuration settings, allowing recipients to customize content, enhancing the weather forecast, adjusting email sending times based on timezones, notifying the admin of unavailable content sources, running the application as a scheduled service, ensuring secure storage of sensitive information, and improving the GUI.
- To save configuration settings, modify the program to store them in a file or database, ensuring they are retained across program restarts.
- Customize the weather forecast for each recipient's location, adjust the sending time of the email digest based on each recipient's timezone, notify the admin of unavailable content sources, and create a persistent application as a scheduled service.
- Additionally, improve the security of the application by finding a more secure way to store sensitive information, such as sender credentials and API keys.
- Enhance the visual appeal and usability of the GUI by refining the layout, adding icons, using color schemes, or incorporating user-friendly features.

Preserving Configuration Settings
- The digest project has introduced two new methods to save information between program runs: a save config method and a load config method.
- The save config method gathers the current state of all GUI elements, saves it to a file using the JSON.dump function, and then calls the update settings method to apply the configuration.
- To integrate these methods, a try-except block is added in the shutdown method to save the current configuration when closing the program.
- A try clause is added in the classes and init method to load the configuration from the JSON file, and if loading fails, the application will use the default settings.
- This feature improves the usability of the digest project and will take about half an hour to implement.
--------------------------------------
