# Introduction-To-Python

Python is a versatile and powerful programming language known for its readability and simplicity. Created by Guido van Rossum and first released in 1991, Python has since become one of the most popular programming languages worldwide. Its ease of learning and extensive libraries make it an excellent choice for beginners and experienced developers alike.

## Key Features

- **Readability:** Python's syntax is clear and concise, making it easy to read and write code. This promotes a clean and maintainable coding style.

- **Versatility:** Python supports both procedural and object-oriented programming paradigms, offering flexibility for various application types.

- **Extensive Libraries:** Python boasts a rich ecosystem of libraries and frameworks, such as NumPy for scientific computing, Django for web development, and TensorFlow for machine learning.

- **Community Support:** The Python community is vast and active, providing a wealth of resources, forums, and documentation. This support makes problem-solving and collaboration easier for developers.

## Use Cases

Python finds applications in a wide range of fields, including:

- **Web Development:** Frameworks like Django and Flask simplify web development tasks.

- **Data Science:** Python is a preferred language for data analysis and machine learning, thanks to libraries like Pandas and scikit-learn.

- **Automation:** Python excels at automating repetitive tasks, making it a popular choice for scripting and automation.

- **Artificial Intelligence:** With libraries like TensorFlow and PyTorch, Python is at the forefront of AI and deep learning research.

## Python Syntax - Basics

- **Indentation:** Crucial for defining code blocks.
- **Variables:** Dynamically typed; no need for explicit declarations.
- **Print Statement:** Use `print()` for console output.

### Data Types

- **Strings:** Declare with single or double quotes.
- **Lists:** Ordered, mutable collections in square brackets.
- **Tuples:** Immutable collections in parentheses.
- **Dictionaries:** Unordered key-value pairs in curly braces.

### Control Flow

- **Conditional Statements:** Use `if`, `elif`, `else`.
- **Loops:** `for` and `while` loops available.

### Functions

- **Function Definition:** Use `def` keyword.
- **Parameters:** Passed in parentheses.

### Exception Handling

- Use `try`, `except`, `finally` for error handling.

### Object-Oriented

- Define classes with `class` keyword.
- Create objects (instances) from classes.

## Data Types

In Python, data types categorize the kinds of values a program can manipulate. The language supports various types, including numeric types like integers, floating-point numbers, and complex numbers, as well as text types like strings. Sequence types encompass ordered collections, such as lists and tuples, with the former being mutable and the latter immutable. Dictionaries serve as a mapping type, allowing the storage of key-value pairs. The boolean type handles truth values with True and False, while the None type represents the absence of a value. Python's flexibility in handling diverse data types contributes to its readability and ease of use, making it a versatile language for a wide range of applications.

### 1. Numeric Types

#### Integers (`int`)

Whole numbers without decimal points.
```python
x = 5
```

#### Floating-Point Numbers (`float`)

Numbers with decimal points.
```python
y = 3.14
```

#### Complex Numbers (`complex`)

Numbers with real and imaginary parts.
```python
z = 2 + 3j
```

### 2. Text Type

#### Strings (`str`)

Ordered sequences of characters.
```python
message = "Hello, Python!"
```

### 3. Sequence Types

#### Lists (`list`)

Ordered, mutable collections.
```python
numbers = [1, 2, 3, 4, 5]
```

#### Tuples (`tuple`)

Ordered, immutable collections.
```python
coordinates = (3, 5)
```

### 4. Mapping Type

#### Dictionaries (`dict`)

Unordered key-value pairs.
```python
student = {"name": "Alice", "age": 25, "grade": "A"}
```

### 5. Boolean Type

#### Boolean (`bool`)

Represents truth values `True` or `False`.
```python
is_python_fun = True
```

### None Type

#### None (`NoneType`)

Represents the absence of a value or a null value.
```python
empty_variable = None
```
## Operators
In Python, operators are symbols or keywords that perform operations on variables and values. Key categories include:

1. **Arithmetic Operators:**
   - Addition `+`
   - Subtraction `-`
   - Multiplication `*`
   - Division `/`
   - Modulus `%` (remainder)
   - Exponentiation `**`
   - Floor Division `//` (integer division)

2. **Comparison Operators:**
   - Equal to `==`
   - Not equal to `!=`
   - Greater than `>`
   - Less than `<`
   - Greater than or equal to `>=`
   - Less than or equal to `<=`

3. **Logical Operators:**
   - Logical AND `and`
   - Logical OR `or`
   - Logical NOT `not`

4. **Assignment Operators:**
   - Assignment `=`
   - Add and assign `+=`
   - Subtract and assign `-=`
   - Multiply and assign `*=`
   - Divide and assign `/=`
   - Modulus and assign `%=`
   - Exponentiate and assign `**=`
   - Floor divide and assign `//=`

5. **Identity Operators:**
   - Identity equal `is`
   - Identity not equal `is not`

6. **Membership Operators:**
   - In `in` (checks if a value exists in a sequence)
   - Not in `not in` (checks if a value does not exist in a sequence)

7. **Bitwise Operators:**
   - Bitwise AND `&`
   - Bitwise OR `|`
   - Bitwise XOR `^`
   - Bitwise NOT `~`
   - Left shift `<<`
   - Right shift `>>`
   
These operators are essential for performing a variety of operations in Python, from basic arithmetic to complex logical and bitwise manipulations.

# Control Flow in Python

Control flow in Python refers to the order in which statements are executed in a program. Key control flow structures include conditional statements and loops. Here's an overview with code snippets focusing on key points:

1. **Conditional Statements:**
   - **if Statement:**
     ```python
     age = 20
     if age >= 18:
         print("You are an adult.")
     else:
         print("You are a minor.")
     ```
   - **elif Statement:**
     ```python
     score = 75
     if score >= 90:
         print("Excellent!")
     elif score >= 70:
         print("Good job!")
     else:
         print("Work harder.")
     ```

2. **Loops:**
   - **for Loop:**
     ```python
     numbers = [1, 2, 3, 4, 5]
     for num in numbers:
         print(num)
     ```
   - **while Loop:**
     ```python
     count = 0
     while count < 5:
         print(count)
         count += 1
     ```

3. **Break and Continue:**
   - **break Statement:**
     ```python
     numbers = [1, 2, 3, 4, 5]
     for num in numbers:
         if num == 4:
             break
         print(num)
     ```
   - **continue Statement:**
     ```python
     numbers = [1, 2, 3, 4, 5]
     for num in numbers:
         if num == 3:
             continue
         print(num)
     ```

4. **Try and Except (Exception Handling):**
   ```python
   try:
       result = 10 / 0
   except ZeroDivisionError:
       print("Cannot divide by zero.")
   else:
       print(result)
   finally:
       print("Execution complete.")
   ```

5. **Ternary Operator:**
   ```python
   age = 20
   status = "Adult" if age >= 18 else "Minor"
   print(status)
   ```

These control flow structures enables the creation of dynamic and responsive programs in Python, allowing developers to execute specific blocks of code based on conditions and iterate through sequences efficiently.

## Python Functions

1. **Function Definition:**
   - Declare a function using the `def` keyword.
   - Example:
     ```python
     def greet(name):
         print(f"Hello, {name}!")
     ```

2. **Function Call:**
   - Call a function by using its name followed by parentheses.
   - Example:
     ```python
     greet("Alice")
     ```

3. **Parameters and Arguments:**
   - Functions can take parameters (inputs).
   - Example:
     ```python
     def add_numbers(a, b):
         return a + b
     result = add_numbers(3, 5)
     ```

4. **Default Parameters:**
   - Assign default values to parameters.
   - Example:
     ```python
     def greet(name, greeting="Hello"):
         print(f"{greeting}, {name}!")
     ```

5. **Return Statement:**
   - Use `return` to send a value back from a function.
   - Example:
     ```python
     def square(num):
         return num ** 2
     ```

6. **Multiple Returns:**
   - Functions can return multiple values.
   - Example:
     ```python
     def calculate(a, b):
         sum_result = a + b
         product_result = a * b
         return sum_result, product_result
     ```

7. **Lambda Functions:**
   - Create small, anonymous functions using the `lambda` keyword.
   - Example:
     ```python
     multiply = lambda x, y: x * y
     ```

8. **Recursion:**
   - Functions can call themselves.
   - Example:
     ```python
     def factorial(n):
         if n == 0 or n == 1:
             return 1
         else:
             return n * factorial(n - 1)
     ```

9. **Global and Local Variables:**
   - Variables inside a function have local scope by default.
   - Example:
     ```python
     global_var = 10

     def print_vars():
         local_var = 5
         print(global_var, local_var)
     ```

10. **Docstrings:**
    - Document functions using docstrings for clarity.
    - Example:
      ```python
      def power(base, exponent):
          """
          Calculate the power of a number.
          :param base: Base number
          :param exponent: Exponent
          :return: Result of the power operation
          """
          return base ** exponent
      ```
These aspects of Python functions allows for the creation of modular, reusable, and well-documented code.

## Introduction to Modules
In Python, a module is a file containing Python definitions and statements. These files can define functions, variables, and classes, and can also include runnable code. The primary purpose of modules is to organize code into reusable and logically structured units. By using modules, developers can break down a large program into smaller, more manageable parts, making the codebase more modular and maintainable. Modules provide a way to encapsulate related functionality, avoid naming conflicts, and facilitate code reuse across different parts of a program or even in other projects. Modules are a fundamental concept in Python's modular programming approach, promoting clarity, organization, and collaboration in software development.

1. **Module Creation:**
   - Create a module by saving a Python script (`.py` file) with functions, variables, or classes.
   - Example: Save the following in a file named `math_operations.py`
     ```python
     def add(a, b):
         return a + b

     def subtract(a, b):
         return a - b
     ```

2. **Module Import:**
   - Import a module using the `import` keyword.
   - Example:
     ```python
     import math_operations

     result = math_operations.add(5, 3)
     ```

3. **Alias for Modules:**
   - Use `as` to create an alias for a module.
   - Example:
     ```python
     import math_operations as math_ops

     result = math_ops.subtract(8, 4)
     ```

4. **Import Specific Items:**
   - Import only specific functions or variables from a module.
   - Example:
     ```python
     from math_operations import add

     result = add(3, 7)
     ```

5. **Module Documentation:**
   - Document modules using docstrings for clarity.
   - Example: Add docstring to `math_operations.py`
     ```python
     """
     A module for basic math operations.
     """

     def add(a, b):
         """
         Add two numbers.
         """
         return a + b

     def subtract(a, b):
         """
         Subtract one number from another.
         """
         return a - b
     ```

6. **Built-in Modules:**
   - Python comes with built-in modules for various functionalities.
   - Example:
     ```python
     import random

     random_number = random.randint(1, 10)
     ```

7. **Package:**
   - A package is a collection of Python modules organized in a directory.
   - Example:
     ```
     my_package/
       __init__.py
       module1.py
       module2.py
     ```
     ```python
     # __init__.py can be an empty file or can include initialization code for the package
     ```
Modules in Python allows for better code organization, reusability, and the ability to leverage external functionality through imports.

## Regular Expressions

In Python, regular expressions, often denoted as regex, serve as a robust mechanism for pattern matching and string manipulation. Leveraging the `re` module, these expressions allow developers to define intricate search patterns, enabling tasks such as locating specific sequences of characters, validating data formats, and extracting information from strings. Regular expressions consist of a combination of special characters and symbols that form rules for matching patterns, providing a concise and powerful means for text processing. Whether validating user input, parsing data, or searching for specific substrings, regular expressions enhance Python's capabilities in handling and manipulating textual data.

1. **Importing the `re` Module:**
   - Import the `re` module to work with regular expressions.
   - Example:
     ```python
     import re
     ```

2. **Basic Patterns:**
   - Regular expressions consist of patterns that define search criteria.
   - Example:
     ```python
     pattern = r"\d+"  # Match one or more digits
     ```

3. **Search Function:**
   - Use `re.search()` to find the first occurrence of a pattern in a string.
   - Example:
     ```python
     text = "The price is $25.99."
     match = re.search(r"\$\d+\.\d{2}", text)
     ```

4. **Match Function:**
   - Use `re.match()` to match the pattern at the beginning of a string.
   - Example:
     ```python
     result = re.match(r"He", "Hello, Python!")
     ```

5. **Findall Function:**
   - Use `re.findall()` to find all occurrences of a pattern in a string.
   - Example:
     ```python
     numbers = re.findall(r"\d+", "There are 10 apples and 5 oranges.")
     ```

6. **Compile Function:**
   - Use `re.compile()` to pre-compile a regex pattern for reuse.
   - Example:
     ```python
     pattern = re.compile(r"\b\w{3}\b")  # Match three-letter words
     ```

7. **Grouping:**
   - Use parentheses to group parts of a pattern.
   - Example:
     ```python
     match = re.search(r"(\d+)-(\d+)-(\d+)", "Date: 2023-11-09")
     ```

8. **Quantifiers:**
   - Quantifiers specify the number of occurrences of a character or group.
   - Example:
     ```python
     pattern = r"\d{2,4}"  # Match 2 to 4 digits
     ```

9. **Character Classes:**
   - Use square brackets to define character classes.
   - Example:
     ```python
     vowels = re.findall(r"[aeiou]", "Hello, Python!")
     ```

10. **Anchors:**
    - Anchors specify the position of a match in a string.
    - Example:
      ```python
      result = re.match(r"^Hello", "Hello, Python!")
      ```

Regular expressions in Python provide a powerful tool for string manipulation, text parsing, and pattern matching. Understanding and using regex can greatly enhance text processing capabilities in Python programs.

# Data Structures
 data structures in Python include:

Python provides a variety of built-in data structures that can be used to organize and manipulate data efficiently. Some of the key data structures in Python include:

1. **Lists:**
   - Ordered, mutable sequences.
   - Example: `my_list = [1, 2, 3, 'a', 'b']`

2. **Tuples:**
   - Ordered, immutable sequences.
   - Example: `my_tuple = (1, 2, 3, 'a', 'b')`

3. **Sets:**
   - Unordered collections of unique elements.
   - Example: `my_set = {1, 2, 3, 'a', 'b'}`

4. **Dictionaries:**
   - Unordered collections of key-value pairs.
   - Example: `my_dict = {'key1': 'value1', 'key2': 'value2'}`

5. **Strings:**
   - Ordered, immutable sequences of characters.
   - Example: `my_string = "Hello, World!"`

6. **Arrays (from the array module):**
   - Homogeneous, fixed-size sequences.
   - Example: `import array; my_array = array.array('i', [1, 2, 3, 4])` (here, 'i' represents integer type)

7. **Queues (from the queue module):**
   - Implements the queue data structure.
   - Example: `from queue import Queue; my_queue = Queue()`

8. **Stacks:**
   - LIFO (Last In, First Out) structures.
   - Can be implemented using lists or the `collections.deque` class.

9. **Heaps (from the heapq module):**
   - Implements the heap queue algorithm.
   - Example: `import heapq; my_heap = [3, 1, 4, 1, 5, 9, 2]; heapq.heapify(my_heap)`

10. **Linked Lists:**
   - Not a built-in type, but can be implemented using custom classes.
   - Consists of nodes, where each node contains data and a reference to the next node.

11. **Deques (from the collections module):**
   - Double-ended queues that support fast O(1) appends and pops from both ends.
   - Example: `from collections import deque; my_deque = deque([1, 2, 3])`

These data structures serve different purposes, and the choice of which one to use depends on the specific requirements of your program. Python's built-in data structures, along with the extensive standard library, provide a powerful foundation for working with data in a variety of applications.

## Pyhton Lists

## Errors and Exceptions

## Classes

# Objects And Classes
