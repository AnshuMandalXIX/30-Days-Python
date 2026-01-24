<div align="center">
  <h1> 🐍 30 Days Of Python</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/company/ai-for-techies">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">

  <sub>Author:
  <a href="https://www.linkedin.com/company/ai-for-techies" target="_blank">AI For Techies</a><br>
  </sub>
</div>
<div align="center">
<img width="8000" height="300" alt="Python Banner" src="https://github.com/user-attachments/assets/989743a6-3b4e-4ad2-a37b-88b9f4ce5264"/>
</div>

# 📘 Day 1: Introduction to Python

**Welcome to Day 1** of your _30 Days of Python journey!_ Today, we are laying the foundation for your programming career. Python is one of the most popular, versatile, and beginner-friendly languages in the world. Its syntax is designed to be readable, almost like English, making it the perfect starting point for any aspiring developer.

To get regular **AI & Tech** updates — stay ahead with the **latest tools, trends, and insights!** 🚀, you may join the [AI For Techies Channel](https://whatsapp.com/channel/0029VbBfR3TCRs1wxJSjOE2z)

## Key Concepts

In today's lesson, we will cover the absolute essentials to get your first script running:

* **Python Syntax:** Understanding the basic structure of a Python file.

* **The `print()` Function:** How to output text and data to the console.

* **Comments:** Writing notes for yourself and others that the computer ignores.

* **Basic Arithmetic:** Using Python as a calculator.

* **String Basics:** How Python handles text (characters inside quotes).

## Code Examples

Copy the following code into your editor. Pay close attention to the comments (lines starting with #), as they explain what each line does.

```shell
# ---------------------------------------------------------
# DAY 1: INTRODUCTION TO PYTHON
# ---------------------------------------------------------

# The print() function displays whatever is inside the parentheses
print("Hello, Python World!")

# You can use single quotes or double quotes for text (strings)
print('Welcome to Day 1 of the 30-Day Challenge.')

# Python can perform mathematical calculations directly
print(10 + 5)   # Addition
print(20 - 7)   # Subtraction
print(4 * 3)    # Multiplication
print(10 / 2)   # Division

# We can combine text and numbers using a comma in the print function
print("The result of 5 + 5 is:", 10)

# Comments (like this line) are ignored by Python. 
# They are used to document your logic.
"""
This is a multi-line comment.
It can span several lines.
Useful for longer explanations!
"""
```

## Execution Steps

To run this code on your computer, follow these simple steps:

1. **Install Python:** Ensure you have Python installed from [python.org](https://python.org).

2. **Open an Editor:** Open a simple text editor (like Notepad or TextEdit) or a code editor like VS Code or PyCharm.

3. **Save the File:** Copy the code above and save it as a file named day1.py. *Note: The .py extension is crucial.*

4. **Open Terminal/Command Prompt:**

* On Windows: Type cmd in the search bar.

* On Mac/Linux: Open the Terminal app.

5. **Navigate and Run:** Use the cd command to go to the folder where you saved the file, then type:

```shell
    python day1.py
```
(On some systems, you may need to type **python3 day1.py**).

## Mini Challenge

Now it's your turn! Create a new file named challenge1.py and write a script that does the following:

1. Print your name to the console.

2. Print a second line that says "I am learning Python for [Reason]", replacing [Reason] with your actual goal.

3. Use the print() function to calculate your age in 10 years (e.g., if you are 25, print 25 + 10).

4. Add a comment at the top of your file with your name and today's date.

# 📘 Day 2: Variables and Built-in Functions

Welcome to **Day 2** of your 30 Days of Python journey! Today, we are going to learn how to store data using variables and how to interact with that data using Python’s powerful "out-of-the-box" tools called **Built-in Functions**.

## Introduction

In programming, a **variable** is like a labeled box where you store information (data). Instead of remembering the data itself, you just remember the name of the box. **Built-in functions** are pre-written pieces of code that Python provides to perform common tasks, such as printing text to the screen, calculating the length of a word, or converting data types.

## Key Concepts

In this lesson, we will cover:

* **Variable Assignment:** Creating names for your data.

* **Naming Conventions:** Rules for naming variables (PEP 8).

* **Common Built-in Functions:** Learning print(), len(), type(), input(), and int().

* **Multiple Assignment:** Assigning several variables in a single line.

## Code Examples

Below is a script demonstrating how variables and functions work together.

```shell
    # --- Variable Assignment ---
# We use the '=' sign to assign a value to a variable name
first_name = "Alex"
last_name = "Smith"
age = 25
is_student = True

# --- Using Built-in Functions ---

# 1. print(): Outputs data to the console
print("Hello, World!") 
print("Name:", first_name, last_name)

# 2. len(): Returns the length of a string or list
name_length = len(first_name)
print("The first name has", name_length, "letters.")

# 3. type(): Checks the data type of a variable
print(type(first_name))  # Output: <class 'str'>
print(type(age))         # Output: <class 'int'>

# 4. input(): Gets information from the user
# Note: input() always returns data as a string
favorite_color = input("What is your favorite color? ")
print("Your favorite color is " + favorite_color)

# 5. Multiple assignment
x, y, z = 10, 20, 30
print(x, y, z)

# --- Naming Rules (PEP 8) ---
# Variables should be lowercase, words separated by underscores
user_home_address = "123 Python Lane"  # Good
UserHomeAddress = "123 Python Lane"    # Avoid (PascalCase is for Classes)
```

## Execution Steps

To run this code on your computer, follow these steps:

1. **Open your Text Editor:** Use VS Code, PyCharm, or even a simple Notepad.

2. **Create a File:** Create a new file and name it **day2.py**.

3. **Copy the Code:** Copy the code block above and paste it into your file.

4. **Open Terminal/Command Prompt:** Navigate to the folder where you saved the file.

5. **Run the Script:** Type the following command and hit Enter:

```shell
    python day2.py
```

6. **Interact:** If you included the **input()** function, the program will wait for you to type something. Type your answer and press Enter to see the rest of the output!

## Mini Challenge: "The Profile Generator"

Now it's your turn! Create a new Python file named challenge2.py and write a script that does the following:

1. Declare a variable for city and country.

2. Use the input() function to ask the user for their hobby.

3. Use the len() function to find the length of their hobby and store it in a variable.

4. Print a summary sentence like: *"I live in Paris, France. My hobby is Coding, which has 6 letters."*

5. Use the type() function to print the data type of your city variable.

**Tip:** Remember that you can combine strings using commas in the print() function!

# 📘 Day 3: Operators in Python

Welcome back to **Day 3** of your 30 Days of Python journey! Yesterday, you learned about variables and data types. Today, we are going to learn how to make our programs *do* something with that data.

## Introduction

In programming, **Operators** are special symbols used to perform operations on variables and values. Think of them as the verbs of the Python language. If variables are the "nouns" (the things we have), operators are the "actions" (what we do with them). Whether you are building a simple calculator or a complex data analysis tool, you will use operators constantly.

## Key Concepts

In this lesson, we will cover the four most essential types of operators:

* **Arithmetic Operators:** Used for mathematical calculations (Addition, Subtraction, Multiplication, etc.).

* **Assignment Operators:** Used to assign or update values to variables.

* **Comparison Operators:** Used to compare two values (Resulting in **True** or **False**).

* **Logical Operators:** Used to combine conditional statements (**and**, **or**, **not**).

## Code Examples

Below is a comprehensive script demonstrating these operators in action.

```shell
    # --- Arithmetic Operators ---
    a = 10
    b = 3
    
    print("--- Arithmetic ---")
    print(f"Addition: {a} + {b} = {a + b}")         # 13
    print(f"Subtraction: {a} - {b} = {a - b}")      # 7
    print(f"Multiplication: {a} * {b} = {a * b}")   # 30
    print(f"Division: {a} / {b} = {a / b}")         # 3.333...
    print(f"Floor Division: {a} // {b} = {a // b}") # 3 (removes decimals)
    print(f"Modulus: {a} % {b} = {a % b}")           # 1 (the remainder)
    print(f"Exponentiation: {a} ** {b} = {a ** b}") # 1000 (10 to the power of 3)
    
    # --- Assignment Operators ---
    print("\n--- Assignment ---")
    x = 5           # Assign 5 to x
    x += 3          # Equivalent to x = x + 3
    print(f"Value of x after += 3: {x}")
    
    # --- Comparison Operators (Returns Boolean) ---
    print("\n--- Comparison ---")
    print(f"Is {a} equal to {b}? {a == b}")         # False
    print(f"Is {a} not equal to {b}? {a != b}")     # True
    print(f"Is {a} greater than {b}? {a > b}")      # True
    
    # --- Logical Operators ---
    # Used to check multiple conditions
    print("\n--- Logical ---")
    is_sunny = True
    is_warm = False
    
    # Both must be True
    print(f"Is it sunny AND warm? {is_sunny and is_warm}") 
    # At least one must be True
    print(f"Is it sunny OR warm? {is_sunny or is_warm}")   
    # Reverses the result
    print(f"Is it NOT sunny? {not is_sunny}")
```

## Execution Steps

To see these operators in action on your own machine, follow these steps:

1. **Open your Editor:** Open VS Code, PyCharm, or even a simple text editor.

2. **Create a New File:** Create a file named **day3_operators.py**.

3. **Copy the Code:** Copy the Python code provided above and paste it into your file.

4. **Save the File:** Ensure you save the file (**Ctrl+S** or **Cmd+S**).

5. **Run the Script:** Open your terminal/command prompt and type:

```shell
    python day3_operators.py
```
6. **Observe the Output:** Read the results in the terminal to see how each operator transformed the numbers and boolean values.

## Mini Challenge: The Area & Perimeter Calculator

Now it's your turn! Put your knowledge to the test with this small project.

**The Task:** Write a script that calculates the **Area and Perimeter** of a rectangle.

1. Create two variables: **length** and **width**. Give them any numeric values.

2. Calculate the **Area** (length multiplied by width).

3. Calculate the **Perimeter** (2 times the length plus 2 times the width).

4. Use a **Comparison Operator** to check if the Area is greater than the Perimeter and print the result.

**Example Output:**
```shell
    Area: 50
    Perimeter: 30
    Is Area greater than Perimeter? True
```

# 📘 Day 4: Master the Art of Strings

Welcome to **Day 4** of our journey! Today, we are diving into one of the most versatile and frequently used data types in programming: **Strings.**

## Introduction

In Python, a **String** is a sequence of characters. Whether it is a single letter, a word, a sentence, or an entire paragraph, if it is wrapped in quotes, it is a string. Python treats strings as "objects," meaning they come with built-in powers (methods) that allow you to manipulate text effortlessly—from changing cases to joining multiple words together.

## Key Concepts

Today, you will learn:

* **Creation:** Defining strings with single, double, and triple quotes.

* **Concatenation:** Gluing strings together.

* **Indexing & Slicing:** Accessing specific parts of a string.

* **String Methods:** Using built-in functions like **.upper()**, **.lower()**, and **.strip()**.

* **Formatting:** The modern way to inject variables into text using **f-strings**.

## Code Examples

```shell
    # --- 1. Creating Strings ---
    simple_string = "Hello, Python!"
    multi_line_string = """This is a string that
    spans across multiple
    lines."""
    
    # --- 2. Concatenation & Repetition ---
    first_name = "Guido"
    last_name = "van Rossum"
    full_name = first_name + " " + last_name  # Using + to combine
    greeting = "Hi! " * 3  # Using * to repeat
    
    # --- 3. Indexing and Slicing ---
    # P  y  t  h  o  n
    # 0  1  2  3  4  5
    language = "Python"
    first_letter = language[0]      # 'P'
    last_letter = language[-1]       # 'n' (negative indexing starts from the end)
    substring = language[0:2]        # 'Py' (starts at 0, goes up to but NOT including 2)
    
    # --- 4. String Methods ---
    text = "  python is fun  "
    print(text.upper())              # "  PYTHON IS FUN  "
    print(text.strip())              # "python is fun" (removes leading/trailing whitespace)
    print(text.replace("fun", "wow")) # "  python is wow  "
    
    # --- 5. F-Strings (Modern Formatting) ---
    # This is the preferred way to format strings in Python 3.6+
    age = 30
    message = f"I am {full_name} and I am {age} years old."
    
    print(full_name)
    print(substring)
    print(message)
```

## Execution Steps

To see this code in action, follow these steps:

1. **Open your editor:** Open VS Code, PyCharm, or even a simple text editor like Notepad.

2. **Create a file:** Create a new file named **day4_strings.py**.

3. **Copy and Paste:** Copy the code block provided above and paste it into your file.

4. **Run the script:**

* Open your terminal or command prompt.

* Navigate to the folder where you saved the file.

* Type **python day4_strings.py** and press **Enter**.

5. **Observe:** Look at the output in the terminal to see how the slicing and formatting changed the text.

## Mini Challenge: "The Secret Agent Name Creator"

Now it is your turn! Write a Python script that does the following:

1. Create a variable called **brand_name** and assign it the value **"Python"**.

2. Create a variable called **version** and assign it the number **3**.

3. Use **slicing** to get the first 3 letters of **brand_name**.

4. Use an **f-string** to print a sentence that looks like this:

**"The first 3 letters of Python are Pyt, and we are using version 3."**

**Tip: Remember that to combine a string and a number in an f-string, you just place the variable name inside the curly braces {}.**

# 📘 Day 5: Python Lists

Welcome to **Day 5** of your journey! So far, we have worked with single values stored in variables. But what happens when you want to store a collection of data, like a shopping list or a list of user names?

Today, we dive into **Lists**, one of the most versatile and frequently used data structures in Python.

## Introduction

A **List** is a built-in Python data structure that is used to store multiple items in a single variable. Lists are:

**Ordered:** They maintain the order in which items are inserted.

**Changeable (Mutable):** You can modify, add, or remove items after the list is created.

**Allow Duplicates:** Since items are indexed, you can have two items with the same value.

## Key Concepts

In this lesson, we will cover:

* How to create a list.

* Accessing items using **indexing** (starting from 0).

* **Slicing** lists to get a sub-section.

* Modifying list items.

* Common list methods: **.append(), .insert(), .remove()**, and **.pop()**.

* Finding the length of a list with **len()**.

## Code Examples

```shell
    # --- 1. Creating a List ---
    fruits = ["apple", "banana", "cherry"]
    numbers = [10, 20, 30, 40, 50]
    mixed_list = ["Python", 2023, True, 3.14]
    
    # --- 2. Accessing Items ---
    # Lists are zero-indexed
    print(f"First fruit: {fruits[0]}")  # apple
    print(f"Last fruit: {fruits[-1]}")   # cherry (negative indexing)
    
    # --- 3. Slicing ---
    # [start:stop] - stop index is not included
    print(f"Slice of numbers: {numbers[1:4]}")  # [20, 30, 40]
    
    # --- 4. Modifying a List ---
    fruits[1] = "blueberry"
    print(f"Updated list: {fruits}")
    
    # --- 5. Adding Items ---
    # .append() adds to the end
    fruits.append("orange")
    
    # .insert() adds at a specific index
    fruits.insert(1, "mango")
    print(f"After additions: {fruits}")
    
    # --- 6. Removing Items ---
    # .remove() deletes a specific value
    fruits.remove("apple")
    
    # .pop() removes an item at a specific index (or the last item if empty)
    deleted_item = fruits.pop(0) 
    print(f"Removed item: {deleted_item}")
    print(f"Final list: {fruits}")
    
    # --- 7. List Length ---
    print(f"Number of fruits remaining: {len(fruits)}")
```

## Execution Steps

To run today's code, follow these simple steps:

1. Open your preferred code editor (like VS Code or PyCharm) or a simple text editor.

2. Create a new file and save it as **day5.py**.

3. Copy and paste the code provided in the **Code Examples** section above into the file.

4. Open your terminal or command prompt.

5. Navigate to the folder where you saved the file.

6. Run the script by typing:
```shell
    python day5.py
```

## Mini Challenge: "The Grocery Manager"

Now it's your turn! Put your new skills to the test with this challenge:

**Task:**

1. Create a list called **groceries** with at least 3 items (e.g., "milk", "eggs", "bread").

2. Print the second item in the list.

3. Add "chocolate" to the **end** of the list.

4. Add "apples" to the **beginning** of the list.

5. Remove "bread" from the list using its name.

6. Print the final list and the total number of items in it.

**Bonus:** Try to print the last item using negative indexing!
