# Intro-to-Python
This module introduces the basics of Python programming, a powerful and easy-to-learn language with efficient high-level data structures and object-oriented approach. Its elegant syntax, dynamic typing, and interpreted nature make it ideal for scripting and rapid application development. The module covers notable Python features, allowing readers to read and write Python modules and programs.

-------------------------------------------------------

# Week 1: Python Syntax

# Day 1
Python is an interpreted language that creates a new executable file when running code. Its interpreter and standard library are available for free on the Python website, which also contains third-party modules and documentation. Python can be easily extended with new functions and data types, making it suitable for customizable applications.

Python in the job market
- Python's market growth is rapidly increasing, making it essential to enhance knowledge and skills in other programming languages, such as CapaCiTi's language courses.
- Python offers diverse job fields, particularly in integrating applications with MySQL, leading some companies like YouTube and BitTorrent to switch to open-source systems.
- Python programming requires extensive knowledge of networking control, and can lead to various fields like Software Engineer, Software developer, Research Analyst, Data Analyst, and Data Scientist.

History of Python
- Python, conceived in the late 1980s by Guido van Rossum in the Netherlands in  December 1989, it is a simple yet reliable programming language with a standard library for various processes.
- Python's syntax prioritizes programmer input, read input, and documentation, balancing fast compilations with readability, making it easier to write applications and maintain readability.
- Python, a C-based programming language, is compatible with various operating systems and is built on concepts from the ABC and Modula-3 languages, ensuring seamless functionality across all environments.

Comments in python
- Comments are a language construct in programming that adds human-readable text to the source code, enhancing its understanding and potentially influencing the compiler and interpreter.
- Comments could be used for a wide range of purposes
     + Augmenting program code with basic descriptions to generate external documentation.
     + Integration with source code management systems and other kinds of external programming tools.
- Python comments, starting with the # hash character, extend to the end of the line, but not within string literals. They clarify code and can be omitted when typing examples.

Creating applications using python
- The Python Interpreter function is explained, followed by creating your first Python application.
- The applications can be created in jupitar notebook or in vscode
- Indentation is crucial for identifying code sections.
- The 'Hello World' program is the first program learned, as it simply says 'Hello World' when run. This course will help you develop your development skills.

--------------------------------------------------------------

# Day 2: Variables

Intoduction to variables
- Variables are temporary storage spaces in computer memory, used by all programming languages to hold different data items or values.
- Understanding variables simplifies programming and helps move data between functions, making it essential for effective programming.
-  Every variable is created with an initial value. A variable can be in three states:
  + Variable creation (Declaration)
  + Variable assignment (Initialization)
  + Variable changed (Execution)
- Python defines variables using the assignment character (=) and naming conventions, making code more readable and easier to understand.
- The rules dictate variable names, which can include upper or lower case letters, numbers, or underscores, but not spaces or whitespace characters.
- Python identifiers are case sensitive and variables cannot have the same name as Python's keywords. To find keywords, use dir() function with __builtins__ attribute.
- The __builtins__ module contains all Python’s built-in attributes, which can be used with the dir()function. The ones that are returned are identified with the following characteristics:
   + Python’s built-in exceptions start with a capital letter.
   + The rest are either functions or data type names.
   + Identifiers that start and end with one or two underscores are special methods.
 
Using Variables
- Variables must be assigned to a data type like string or integer, with additional data types to be discussed later.
- Python's assignment feature automatically assigns variables to appropriate data types, such as string data-types, allowing for manipulation of the same type. It can also cast values into common types, though explicit casting is required for some cases.

Casting
- Casting can be done in two ways:
   + Implicitly: The compiler automatically casts a value from one data type to another when assured that there will be no data loss.
   + For example. casting from an integer variable to a floating-point variable or casting from an integer variable to another integer variable
   + Explicitly: A value cannot be automatically cast from one data type to another if it will result in data loss. Extra code has to be written to ensure that the value stays the same and only the data type changes.
   + For example, casting from a floating-point value to an integer value
- The third printed line casts a string to a float successfully, because s_number is in the correct format. The rules to convert a string to a float are:
  + The string should only contain numbers.
  + Other than numbers the following are allowed:
  + Only one dot (.) character. Indicates the decimal starts after the dot (.) character.
  + A ‘+’ or ‘−‘ character at the beginning of the string. This indicates that the number is either positive or negative.

--------------------------------------------------------------

# Day 3: Data types

Introduction to Data Types
- Python uses three data types, each with unique functions. The choice of the wrong data type can significantly impact a computer's performance.
- Data types covered in this course include:
   + Integers
   + Booleans
   + Floating point numbers
   + Complex numbers
   + Strings
- Literals are an alternative to using variables. Examples of literals include:
   + "This is only a string"
   + "\t"
   + 2

Intergers
- Python has three distinct numeric types: integers, negative and positive numbers, and monetary numbers with decimal values, ensuring performance efficiency in programs.
- Python is a static language, as it assigns values of a specific type to specific variables based on their assigned data types.
- Integers are always whole numbers. Integers include negative and positive numbers. The only factor that determines the range of an integer variable is the amount of memory a machine has available.
- The four main calculation operators are '+', '-', '*', and '/', with the plus operator being universally applicable for adding numbers and concatenating strings.
- Programs previously used fixed values for output manipulation, but now require user input for accurate output, achieved through the input() command in real-life situations.

Booleans
- Boolean data type has integer values and can have True or False values. Python uses case-sensitive True and False operators to test valid conditions between arguments.
   + The and-operator
   + The or operator
   + The not operator
- The next section will refresh your memory, and you will soon be able to write programs that execute operations automatically based on decisions (such as the if statement explained in week 2). The following variable values are considered False:
   + False
   + None
   + Zero for any numeric data type, 0, 0.0, 0j
   + An empty sequence or mapping. Like a list or tuple, ' ', ( ), [ ], { }
   + Instances of user-defined classes, where a class that defines a __bool__() method returns zero or False.
 
Floating point numbers
- Floating point numbers are better known as floats.
- Float is a data type that accurately manages decimal places and can be used as a function with zero or 1 argument. It returns 0.0 without an argument, but may raise exceptions.
- A string value cast to a float must contain only numbers and only one occurrence of the dot (.) character.
- The f in the format part of the print statement indicates that the number to be formatted is a float.
- The + sign indicates that the changed amount must be signed, which means that if the dollar compared to the rand decreases, that a − sign would be printed before the amount difference.

Complex numbers
- Float manages decimal places in complex numbers, which are two numbers in a single variable. They consist of the real and imaginary parts, assigned in complex(real, image). Python supports complex numbers, written as 4+8j.
- Complex numbers are used in Python to combine two numbers into one manageable number. The following example shows how complex numbers are used in a simple manner.
- The absolute value of a complex number is its magnitude, calculated using the Pythagorean theorem.
- The text defines a complex number, with real numbers 4 and imaginary numbers 8. Two integers are declared, and complex numbers accept floating-point numbers. Lines 6 and 7 print the numbers, while lines 10 and 12 demonstrate manipulation and real values are added separately.

String
- Strings are Unicode characters that form a manageable string, represented by the immutable str data type. They can be created with no argument, returning an empty string, or as a string representation of a supplied type. The string function is commonly used to convert other data types to strings.
- Using the ‘+=‘ operator with strings
   + The ‘+=‘ operator adds values to an existing variable
- Using the end of line escape sequence
   + The end of line escape sequence (\) can also help to make code more readable.
- Enclose the expression in brackets
   + The easiest way to write code in an easily readable format is by enclosing the expression in brackets.

Lambda Expressions
- Lambda functions are small anonymous functions that return the sum of arguments, are syntactically restricted to a single expression, and can reference variables from the containing scope.

Conventions about the content and formatting of documentation strings
- 
