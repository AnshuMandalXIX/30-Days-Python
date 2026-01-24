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

# 📘 Day 6: Tuples in Python

Welcome back to **Day 6** of your journey! Yesterday, we explored Lists, which are flexible and changeable. Today, we are going to learn about their "structured" cousins: **Tuples**.

In Python, a tuple is a collection that is ordered and **immutable** (unchangeable). Once you create a tuple, you cannot change, add, or remove items. This makes them perfect for data that should never be altered throughout your program.

## Key Concepts

In this lesson, we will cover:

* **Syntax:** How to define a tuple using parentheses **()**.

* **Immutability:** Understanding why and how tuples remain constant.

* **Indexing and Slicing:** Accessing specific elements within a tuple.

* **Tuple Packing & Unpacking:** A powerful Python feature for assigning variables.

* **Common Methods:** Learning **count()** and **index()**.

## Code Examples

The following code demonstrates the most important operations you can perform with tuples.

```shell
    # 1. Creating Tuples
    # Tuples are defined using parentheses ()
    fruits = ("apple", "banana", "cherry", "apple")
    print(f"Fruit Tuple: {fruits}")
    
    # Note: To create a tuple with only ONE item, you must include a trailing comma
    single_item_tuple = ("orange",)
    print(f"Single item: {type(single_item_tuple)}")
    
    # 2. Accessing Elements
    # Like lists, tuples use zero-based indexing
    print(f"First fruit: {fruits[0]}")
    print(f"Last fruit: {fruits[-1]}")
    
    # 3. Immutability (The 'Immutable' Rule)
    # The following line would raise a TypeError:
    # fruits[1] = "mango" 
    
    # 4. Tuple Unpacking
    # You can extract values into variables in one line
    coordinates = (10, 20, 30)
    x, y, z = coordinates
    print(f"Unpacked values - X: {x}, Y: {y}, Z: {z}")
    
    # 5. Useful Tuple Methods
    # Since tuples can't change, they only have two built-in methods
    print(f"How many apples? {fruits.count('apple')}")
    print(f"Index of 'cherry': {fruits.index('cherry')}")
    
    # 6. Joining Tuples
    # You can't change a tuple, but you can combine two to make a new one
    vegetables = ("carrot", "potato")
    food_basket = fruits + vegetables
    print(f"Combined Basket: {food_basket}")
```

## Execution Steps

To run this code on your local machine, follow these steps:

1. **Open your Text Editor:** Use VS Code, Atom, or even a simple Notepad.

2. **Create a New File:** Save the file as **day6.py**.

3. **Copy and Paste:** Copy the code block above and paste it into your file.

4. **Open Terminal/Command Prompt:** Navigate to the folder where you saved the file.

5. **Run the Script:** Type the following command and press Enter:
```shell
    python day6.py
```

## Mini Challenge: The "Traveler's Log"

Now it's your turn to practice! Write a script that performs the following:

1. Create a tuple called **destination** containing a city name, a country, and the year you visited (e.g., **"Paris", "France", 2022**).

2. Unpack the tuple into three variables: **city, country, and year**.

3. Print a formatted string like: *"I visited Paris, France in 2022."*

4. Try to change the **year** in the tuple to **2024** and observe the error message Python gives you. (Remember to comment out the error-causing line so the rest of your script can run!)

**Expert Tip:** Use tuples when you want to protect your data from accidental changes. They are also slightly faster than lists, which makes them great for performance in large programs!

# 📘 Day 7: Master the Power of Sets

Welcome to **Day 7** of your journey! Today, we are exploring one of the most unique and efficient data types in Python: **Sets**.

In the previous days, we covered Lists and Tuples. While Lists are ordered and allow duplicates, Sets are the specialists of **uniqueness** and **mathematical operations**. If you have ever needed to remove duplicates from a list or find what two groups have in common, Sets are your best friend.

## Introduction

A **Set** is an unordered collection of unique elements. Think of a set like a bag of labeled balls: you can’t have two balls with the same label, and because they are just sitting in a bag, they don’t have a specific "first" or "last" position.

**Why use Sets?**

* They automatically handle duplicate data.

* They are highly optimized for checking if an item exists within them (membership testing).

* They allow for mathematical operations like Union, Intersection, and Difference.

## Key Concepts

In this lesson, we will cover:

* **Creating Sets:** Using curly braces **{}** and the **set()** constructor.

* **Unique Property:** How sets automatically discard duplicates.

* **Modifying Sets:** Adding and removing items.

* **Set Operations:** Joining sets, finding overlaps, and identifying differences.

* **Clearing and Deleting:** Emptying or removing a set entirely.

## Code Examples

```shell
    # --- 1. Creating a Set ---
    # Sets are defined with curly braces {}
    fruits = {"apple", "banana", "cherry", "apple"}
    
    # Notice that "apple" was added twice, but when we print it:
    print(f"Unique fruits: {fruits}")  # Output will only show one 'apple'
    
    # --- 2. Adding and Updating ---
    # Adding a single item
    fruits.add("orange")
    
    # Adding multiple items using update()
    fruits.update(["mango", "grape"])
    print(f"After updates: {fruits}")
    
    # --- 3. Removing Items ---
    # remove() raises an error if the item is not found
    fruits.remove("banana")
    
    # discard() does NOT raise an error if the item is missing
    fruits.discard("watermelon") 
    print(f"After removals: {fruits}")
    
    # --- 4. Mathematical Set Operations ---
    st1 = {"item1", "item2", "item3", "item4"}
    st2 = {"item3", "item4", "item5", "item6"}
    
    # Union: Combine both (removes duplicates)
    all_items = st1.union(st2)
    print(f"Union: {all_items}")
    
    # Intersection: Items present in BOTH sets
    common_items = st1.intersection(st2)
    print(f"Intersection: {common_items}")
    
    # Difference: Items in st1 but NOT in st2
    diff_items = st1.difference(st2)
    print(f"Difference: {diff_items}")
    
    # --- 5. Converting between types ---
    # A common trick to remove duplicates from a list
    numbers_list = [1, 2, 2, 3, 4, 4, 5]
    unique_numbers = list(set(numbers_list))
    print(f"List with duplicates removed: {unique_numbers}")
```

## Execution Steps

To run this code and see the results for yourself:

1. **Open your Editor:** Open VS Code, PyCharm, or even a simple text editor.

2. **Create the File:** Create a new file and save it as **day7_sets.py**.

3. **Copy the Code:** Copy the Python code block provided above and paste it into your file.

4. **Run via Terminal:** Open your terminal or command prompt and navigate to the folder where you saved the file.
   Type the following and press Enter:

```shell
    python day7_sets.py
```
5. **Observe the Output:** Pay close attention to how the order of items in your output might differ from the code—this is because sets are **unordered!**

## Mini Challenge: The Guest List

Imagine you have two lists of guests for two different parties. Some people are invited to both.

1. Create a set named **party_a** with: "Alice", "Bob", "Charlie", "Dave".

2. Create a set named **party_b** with: "Charlie", "Dave", "Eve", "Frank".

3. Use a set method to find out which guests are invited to **both** parties (Intersection).

4. Use a set method to find a list of **all unique guests** attending either party (Union).

5. Use a set method to find guests who are **only** invited to **party_a** but not **party_b** (Difference).

**Bonus:** Add your own name to **party_a** using the **.add()** method!

# 📘 Day 8: Master of Mappings – Dictionaries

Until now, we have used **Lists** and **Tuples** to store sequences of data. However, in the real world, data is often descriptive. Instead of just a list of values, we need "key-value" pairs. Think of a real-life dictionary: you look up a **word** (the key) to find its **definition** (the value).

In Python, a **Dictionary** is an unordered, changeable (mutable), and indexed collection that stores data in pairs.

## Key Concepts

In this lesson, we will cover:

* **Creating Dictionaries:** Using curly braces **{}** and the **dict()** constructor.

* **Accessing Items:** How to retrieve values using keys or the **.get()** method.

* **Modifying Dictionaries:** Adding, updating, and removing items.

* **Dictionary Methods:** Essential functions like **.keys()**, **.values()**, and **.items()**.

* **Nested Dictionaries:** Storing a dictionary inside another dictionary.

## Code Examples

Let’s dive into the syntax. Pay close attention to the **key: value** structure.

```shell
    # 1. Creating a Dictionary
    # Keys are usually strings, values can be any data type
    student = {
        "name": "Alice Smith",
        "age": 21,
        "course": "Computer Science",
        "skills": ["Python", "SQL", "Math"]
    }
    
    print(f"Student Data: {student}")
    
    # 2. Accessing Values
    # Accessing using the key inside square brackets
    print(f"Name: {student['name']}")
    
    # Accessing using the .get() method (Safer: returns None if key doesn't exist)
    email = student.get("email", "Email not found")
    print(f"Email Status: {email}")
    
    # 3. Modifying and Adding Items
    student["age"] = 22  # Updating an existing value
    student["graduated"] = False  # Adding a new key-value pair
    print(f"Updated Student: {student}")
    
    # 4. Removing Items
    # .pop() removes the item with the specified key
    removed_value = student.pop("course")
    print(f"Removed Course: {removed_value}")
    
    # 5. Iterating through a Dictionary
    print("\n--- Dictionary Iteration ---")
    for key, value in student.items():
        print(f"{key.capitalize()}: {value}")
    
    # 6. Nested Dictionaries
    classroom = {
        "student_1": {"name": "Bob", "grade": "A"},
        "student_2": {"name": "Eve", "grade": "B+"}
    }
    print(f"\nStudent 1 Name: {classroom['student_1']['name']}")
```

## Execution Steps

To run the code above and see the results on your machine, follow these steps:

1. **Open your IDE:** Open VS Code, PyCharm, or even a simple text editor.

2. **Create the file:** Create a new file named **day8.py**.

3. **Copy the code:** Copy the Python code provided in the "Code Examples" section above and paste it into your file.

4. **Run the script:**

* Open your terminal or command prompt.

* Navigate to the folder where you saved the file.

* Type python **day8.py** and press **Enter**.

5. **Observe the output:** You will see how Python manages the data and handles the changes we made to the **student** object.

## Mini Challenge

Now it's your turn to practice!

**Task:** Create a dictionary called car.

1. Add the following keys: brand, model, and year. Give them appropriate values.

2. Add a new key called color with a value of your choice.

3. Change the year to 2024.

4. Use the .pop() method to remove the model from the dictionary.

5. Print the final dictionary to the console.

**Bonus:** Try to print only the keys of your dictionary using the **.keys()** method.

# 📘 Day 9: Master the Logic – Conditionals in Python

**Conditionals** allow your code to make decisions. Depending on whether a condition is true or false, your program can choose different paths. This is the foundation of logic in programming.

## Key Concepts

In this lesson, we will cover:

* **Boolean Logic:** The foundation of **True and **False**.

* The **`if`** statement: Executing code only if a condition is met.

* The **`else`** statement: Providing an alternative path.

* The **`elif`** statement: Checking multiple conditions in sequence.

* **Logical Operators:** Using **and, or,** and **not** to combine conditions.

* **Nested Conditionals:** Placing one decision inside another.

## Code Examples

The following script demonstrates a basic "Grading System" to show how these concepts work together.

```shell
    # Day 9: Conditionals Practice - Grading System
    
    # 1. Basic if-else
    age = 18
    if age >= 18:
        print("You are eligible to vote!")
    else:
        print("You are too young to vote.")
    
    # 2. The if-elif-else ladder
    score = 85
    
    if score >= 90:
        grade = "A"
    elif score >= 80:
        grade = "B"
    elif score >= 70:
        grade = "C"
    else:
        grade = "F"
    
    print(f"Your score is {score}, which is a grade: {grade}")
    
    # 3. Logical Operators (and, or)
    is_weekend = True
    is_sunny = False
    
    if is_weekend and is_sunny:
        print("Let's go to the beach!")
    elif is_weekend and not is_sunny:
        print("It's the weekend, but maybe stay inside and code.")
    else:
        print("It's a workday, back to the office!")
    
    # 4. Nested Conditionals
    # Checking if a number is positive and then if it is even
    number = 10
    
    if number > 0:
        print("The number is positive.")
        if number % 2 == 0:
            print("It is also an even number.")
        else:
            print("It is an odd number.")
    else:
        print("The number is not positive.")
```

## Execution Steps

To run the code above and see the logic in action, follow these steps:

1. **Open your Editor:** Open VS Code, PyCharm, or any text editor.

2. **Create the File:** Create a new file named **day9.py**.

3. **Copy and Paste:** Copy the code block provided above and paste it into your file.

4. **Run the Script:** Open your terminal or command prompt and type:
```shell
    python day9.py
```

5. **Observe:** Look at the output in the terminal. Try changing the values of **score or age** in the script, save it, and run it again to see how the output changes!

## Mini Challenge: The "Weather Adviser"

Now it's your turn! Write a small program that asks the user for the current temperature and suggests an activity.

**Requirements:**

1. Use the input() function to get the temperature from the user (remember to convert it to an integer using int()).

2. Use if, elif, and else logic:

If the temperature is above 30°C, print: "It's hot! Stay hydrated."

If the temperature is between 15°C and 30°C (inclusive), print: "The weather is perfect for a walk."

If the temperature is below 15°C, print: "Grab a jacket, it's chilly!"

**Check your logic:** Make sure you use the comparison operators **(>, <, >=)** correctly!

# 📘 Day 10: Mastering Loops in Python

In programming, we often need to repeat a specific block of code multiple times. Instead of writing the same line over and over again, we use **Loops**. Loops allow us to automate repetitive tasks, iterate over collections of data (like lists), and run logic until a certain condition is met. In Python, there are two primary types of loops: **for** loops and **while** loops.

## Key Concepts

* **The `for` loop:** Used for iterating over a sequence (list, tuple, string, or range).

* **The `range()` function:** Generating sequences of numbers.

* **The `while` loop:** Used for repeating code as long as a condition is **True**.

* **Loop Control:** Using break to exit a loop and continue to skip an iteration.

* **Nested Loops:** Running a loop inside another loop.

## Code Examples

## The `for` Loop

The **for** loop is ideal when you know how many times you want to run a block of code or when you are processing items in a collection.

```shell
    # Iterating through a list of fruits
    fruits = ["apple", "banana", "cherry"]
    
    print("--- Fruit List ---")
    for fruit in fruits:
        print(f"I love eating {fruit}!")
    
    # Using range(start, stop, step)
    # This will print numbers from 1 to 5
    print("\n--- Counting 1 to 5 ---")
    for i in range(1, 6):
        print(f"Number: {i}")
```

## The `while` Loop

A **while** loop continues to execute as long as its condition remains **True**. Be careful not to create "infinite loops"!

```shell
    # A simple countdown
    count = 5
    
    print("--- Countdown ---")
    while count > 0:
        print(count)
        count -= 1  # Important: decrement count to eventually end the loop
    print("Blast off! 🚀")
```

## Break and Continue

Sometimes you need to interrupt the normal flow of a loop.

```shell
    print("--- Break and Continue ---")
    for n in range(1, 11):
        if n == 3:
            continue  # Skip the rest of this iteration (skips number 3)
        if n == 7:
            break     # Exit the loop entirely when we hit 7
        print(f"Processing: {n}")
```

## Nested Loops

You can place a loop inside another loop. The "inner" loop will complete all its iterations for every single iteration of the "outer" loop.

```shell
    # Multiplication Table (1 to 3)
    print("--- Multiplication Table ---")
    for i in range(1, 4):       # Outer loop
        for j in range(1, 4):   # Inner loop
            print(f"{i} x {j} = {i * j}")
        print("---")
```

## Execution Steps

To run these examples on your machine, follow these steps:

1. Open your preferred code editor (like VS Code, PyCharm, or even a text editor like Notepad).

2. Create a new file named **day10.py**.

3. Copy and paste the code examples provided above into the file.

4. Open your terminal or command prompt.

5. Navigate to the folder where you saved the file.

6. Run the script by typing:
```shell
    python day10.py
```

## Mini Challenge: "The Power of 2"

Now it's your turn! Write a Python script that uses a loop to solve the following problem:

**The Task:**

1. Use a **for** loop and the **range()** function.

2. Calculate and print the square (number multiplied by itself) of every number from 1 to 10.

3. Bonus: If the square is greater than 50, print a message saying "That's a big square!" next to the result.

**Expected Output Snippet:**
```shell
    1 squared is 1
    2 squared is 4
    ...
    8 squared is 64. That's a big square!
```

# 📘 Day 11: Functions in Python

A function is a reusable block of code that performs a specific task. You can think of a function like a kitchen appliance: you provide the ingredients (input), it performs a specific action (process), and it gives you a result (output).

The core philosophy of using functions is **DRY** (Don't Repeat Yourself). Instead of writing the same code ten times, you define it once in a function and "call" it whenever you need it.

## Key Concepts

In this lesson, we will cover:

* **Defining a function:** Using the **def** keyword.

* **Calling a function:** How to execute the code inside a function.

* **Parameters and Arguments:** Passing information into a function.

* **Return Values:** Getting data back from a function.

* **Default Parameters:** Setting "fallback" values for arguments.

## Code Examples

Study the following examples to see how functions are structured in Python.

```shell
    # --- Example 1: A Simple Function ---
    def greet_user():
        """This function prints a simple greeting."""
        print("Hello! Welcome to Day 11 of Python.")
    
    # To execute the code inside, we must "call" the function
    greet_user()
    
    # --- Example 2: Functions with Parameters ---
    def greet_by_name(name):
        """This function takes a name as an input and greets the user."""
        print(f"Hello, {name}! Glad to see you.")
    
    # 'Alice' is the argument being passed into the parameter 'name'
    greet_by_name("Alice")
    
    # --- Example 3: Returning a Value ---
    def add_numbers(a, b):
        """This function adds two numbers and returns the result."""
        result = a + b
        return result
    
    # We can store the returned value in a variable
    sum_total = add_numbers(10, 5)
    print(f"The sum is: {sum_total}")
    
    # --- Example 4: Default Parameters ---
    def describe_pet(pet_name, animal_type="dog"):
        """Displays information about a pet. animal_type defaults to 'dog'."""
        print(f"I have a {animal_type} named {pet_name}.")
    
    # Using the default value
    describe_pet("Buddy") 
    
    # Overriding the default value
    describe_pet(pet_name="Whiskers", animal_type="cat")
```

## Execution Steps

To run these examples on your own machine, follow these steps:

1. Open your favorite code editor (like VS Code, PyCharm, or even a simple text editor).

2. Create a new file and name it **day11_functions.py**.

3. Copy and paste the code examples provided above into the file.

4. Open your terminal or command prompt.

5. Navigate to the folder where you saved the file.

6. Run the script by typing:
```shell
    python day11_functions.py
```

7. Observe the output in the console to see how the functions interact.

## Mini Challenge: The Area Calculator

Now it's your turn to practice! Your task is to create a small utility script.

**Task:** Write a function called **calculate_area** that takes two parameters: **length and width**.

1. The function should multiply the length and width.

2. The function should **return** the result.

3. Call the function with the values 15 and 10.

4. Print a formatted string that says: **"The area of the rectangle is: [result] square units."**

**Bonus:** Try calling the function using your own custom dimensions!

# 📘 Day 12: Modules in Python

As your Python programs grow in size, keeping all your code in a single file becomes messy and difficult to manage. A **Module** is simply a file containing Python definitions and statements (functions, variables, or classes) that you can use in other scripts.

Think of a module as a "toolbox." Instead of building every tool from scratch, you can import existing toolboxes to save time and keep your code clean, modular, and reusable.

##  Key Concepts

In this lesson, we will cover:

* **Built-in Modules:** Using Python's pre-installed libraries (like math and random).

* **Custom Modules:** Creating your own .py files and importing them.

* **Import Variations:** Using import, from ... import, and as (aliasing).

* **The `dir()` function:** Inspecting what is inside a module.

## Code Examples

#### A. Using Built-in Modules
Python comes with a "Standard Library" full of modules ready for use.

```shell
    import math
    import random
    
    # Using the math module for square roots and constants
    print(f"The value of Pi is: {math.pi}")
    print(f"The square root of 64 is: {math.sqrt(64)}")
    
    # Using the random module to generate a random integer
    lucky_number = random.randint(1, 100)
    print(f"Your lucky number today is: {lucky_number}")
```

#### B. Creating and Importing a Custom Module
Imagine you have a file named calculator.py with the following content:
```shell
    # Save this as calculator.py
    def add(a, b):
        return a + b
    
    def multiply(a, b):
        return a * b
```

Now, you can import it into your main script:
```shell
    # main.py
    import calculator
    
    # Using the functions from our custom module
    result_sum = calculator.add(10, 5)
    result_product = calculator.multiply(10, 5)
    
    print(f"Sum: {result_sum}")       # Output: 15
    print(f"Product: {result_product}") # Output: 50
```

#### C. Import Variations
You don't always have to import the whole module. You can pick exactly what you need.

```shell
    # 1. Importing specific functions (no need to use 'module.function()')
    from math import pi, pow
    
    print(pow(2, 3)) # 2 raised to the power of 3
    
    # 2. Renaming a module with an alias (standard practice for some libraries)
    import statistics as stats
    
    data = [1, 2, 3, 4, 100]
    print(stats.mean(data)) # Calculates the average
```

## Execution Steps

To see modules in action on your computer, follow these steps:

1. **Create the Module:** Open your code editor and create a file named mymodule.py. Paste a simple function inside it (like a greeting function).

2. **Create the Main Script:** In the same folder, create another file named **app.py**.

3. **Import:** Inside app.py, write import mymodule and call your function.

4. **Run:** Open your terminal or command prompt, navigate to that folder, and type:
```shell
    python app.py
```

5. **Observe:** Python will look in the current directory, find mymodule.py, and execute the code you requested!

## Mini Challenge: The "Geometry Expert"

**Task:**

1. Create a module named geometry.py.

2. Inside it, write two functions:

* area_of_circle(radius): Returns $\pi \times r^2$ (Use math.pi).

* area_of_square(side): Returns $side \times side$.

3. Create a second file named test_geo.py.

4. Import your functions and print the area of a circle with a radius of 7 and a square with a side of 12.

**Bonus:** Use dir(math) in your script to see all the other mathematical functions Python offers!

# 📘 Day 13: List Comprehension

List comprehension is a compact syntax for generating new lists. It allows you to perform operations on each item in a sequence and filter items based on conditions—all within a single line of code.

**The Syntax:**

**new_list = [expression for item in iterable if condition]**

* **Expression:** What you want to do to the item (the output).

* **Item:** The variable representing the element in the iterable.

* **Iterable:** The list, range, or string you are looping through.

* **Condition (Optional):** A filter to decide if the item should be included.

## Key Concepts

* Converting a standard **for** loop into a list comprehension.

* Applying mathematical operations to list elements.

* Filtering data using **if** statements within the comprehension.

* Using list comprehension with strings.

## Code Examples

#### Example 1: Basic List Comprehension
Let's compare a traditional loop with a list comprehension.

```shell
    # Traditional Way: Squaring numbers 0-5
    squares = []
    for x in range(6):
        squares.append(x**2)
    
    print(f"Traditional: {squares}")
    
    # List Comprehension Way
    # [expression for item in iterable]
    squares_comp = [x**2 for x in range(6)]
    
    print(f"Comprehension: {squares_comp}")
```


#### Example 2: Adding a Condition (Filtering)
You can add an **if** statement at the end to filter which items get added to the new list.

```shell
    # Create a list of even numbers from 0 to 10
    evens = [n for n in range(11) if n % 2 == 0]
    
    print(f"Even numbers: {evens}")
    
    # Extracting names that start with 'A'
    names = ["Alice", "Bob", "Amanda", "Charlie", "Austin"]
    a_names = [name for name in names if name.startswith("A")]
    
    print(f"Names starting with A: {a_names}")
```

#### Example 3: String Manipulation
List comprehension is great for cleaning up or transforming text data.

```shell
    languages = ["python", "java", "javascript", "c++"]
    
    # Convert all strings to uppercase
    upper_languages = [lang.upper() for lang in languages]
    
    print(f"Uppercase: {upper_languages}")
```

## Execution Steps

To see these examples in action, follow these steps:

1. Open your preferred code editor (VS Code, PyCharm, or even a text editor).

2. Create a new file named **day13.py**.

3. Copy and paste the code examples provided above into the file.

4. Open your terminal or command prompt.

5. Navigate to the directory where you saved the file.

6. Run the script using the command:
```shell
    python day13.py
```

## Mini Challenge: The "Positive Multiples" Task

Now it's your turn to practice!

**The Goal:** Given a list of numbers, create a new list that contains the **triple** of every **positive** number (numbers greater than zero).

**Input List:**
```shell
    numbers = [-5, 3, -1, 10, 2, 0, -8]
```

**Instructions:**

1. Use list comprehension to filter out numbers that are 0 or less.

2. Multiply the remaining numbers by 3.

3. Print the resulting list.

*Hint: Your final list should look like [9, 30, 6].*

# 📘 Day 14: Higher-Order Functions

In Python, functions are treated as **First-Class Citizens**. This means functions can be treated just like any other object (like integers or strings).

A **Higher-Order Function** is a function that does at least one of the following:

* Takes one or more functions as arguments.

* Returns a function as its result.

This allows us to create powerful abstractions, such as "wrappers" or "filters," that can be applied to many different parts of our logic.

## Key Concepts

* **Functions as Parameters:** Passing one function into another.

* **Nested Functions:** Defining a function inside another function.

* **Functions as Return Values:** A function generating and "giving back" a new function.

* **Built-in Higher-Order Functions:**

* **map():** Applying a transformation to every item in an iterable.

* **filter():** Filtering items out of an iterable based on a condition.

* **reduce():** Rolling a list of values into a single cumulative result.

## Code Examples

#### A. Passing a Function as an Argument

```shell
    def uppercase(text):
        return text.upper()
    
    def greet(func):
        # This is a higher-order function because it takes 'func' as a parameter
        greeting = func("Hello, I am learning Python!")
        print(greeting)
    
    # Note: We pass 'uppercase' without parentheses so we pass the function itself
    greet(uppercase)
```

#### B. The Map and Filter Functions

```shell
    numbers = [1, 2, 3, 4, 5, 6]
    
    # 1. Map: Square every number in the list
    # map(function, iterable)
    squares = list(map(lambda x: x**2, numbers))
    print(f"Squares: {squares}")
    
    # 2. Filter: Only keep even numbers
    # filter(function, iterable)
    evens = list(filter(lambda x: x % 2 == 0, numbers))
    print(f"Evens: {evens}")
```

#### C. Function Returning a Function (Closures)

```shell
    def make_multiplier(n):
        """Returns a function that multiplies its input by n."""
        def multiplier(x):
            return x * n
        return multiplier
    
    # Create a function that doubles numbers
    double = make_multiplier(2)
    # Create a function that triples numbers
    triple = make_multiplier(3)
    
    print(f"Double 5: {double(5)}")  # Output: 10
    print(f"Triple 5: {triple(5)}")  # Output: 15
```

## Execution Steps

1. **Install Python:** Ensure you have Python installed on your machine.

2. **Create a File:** Open your favorite code editor (VS Code, PyCharm, or even a text editor) and create a new file named **day14.py**.

3. **Copy and Paste:** Copy the code examples provided above into your file.

4. **Run the Script:** Open your terminal or command prompt, navigate to the folder where you saved the file, and run:

```shell
    python day14.py
```
5. **Observe:** Check the output in your terminal to see how the mapping, filtering, and function generation work.

## Mini Challenge

**The Task:**

You are given a list of names: **names = ["Alice", "Bob", "Charlie", "David", "Eve"].**

1. Use **filter()** to create a new list containing only names that have more than 4 characters.

2. Use **map()** to convert that filtered list to all uppercase letters.

3. Print the final result.

*Hint: You can chain them together or do it in two steps!*

# 📘 Day 15: Python Errors and Exception Types

When you write code that violates the rules of the Python language, the interpreter raises an error. These generally fall into two categories:

1.  **Syntax Errors:** The "grammar" of your code is wrong (e.g., a missing colon).

2. **Exceptions:** The syntax is correct, but something went wrong during execution (e.g., trying to divide by zero).

Today, we will focus on identifying the most common built-in exceptions so you can recognize them on sight.

## Key Concepts

In this tutorial, we will cover the following common error types:

* **SyntaxError**: Invalid syntax.

* **NameError**: Using a variable that hasn't been defined.

* **TypeError**: Performing an operation on an incorrect data type.

* **IndexError**: Accessing an index that is out of range in a list.

* **KeyError**: Accessing a dictionary key that doesn't exist.

* **AttributeError**: Calling a method that doesn't exist for that object.

* **ZeroDivisionError**: Dividing a number by zero.

## Code Examples

The following script demonstrates how these errors are triggered.

```shell
    # Day 15: Python Errors and Exceptions
    
    # 1. SyntaxError: Occurs when the code is not formatted correctly.
    # Uncomment the line below to see: it's missing a closing quote.
    # print("Hello World) 
    
    # 2. NameError: Occurs when a variable is used before it's defined.
    try:
        print(my_variable)
    except NameError as e:
        print(f"NameError caught: {e}")
    
    # 3. TypeError: Occurs when an operation is applied to an object of inappropriate type.
    try:
        # Adding an integer and a string
        result = 10 + "20"
    except TypeError as e:
        print(f"TypeError caught: {e}")
    
    # 4. IndexError: Occurs when trying to access an index outside a list's range.
    numbers = [1, 2, 3]
    try:
        print(numbers[5])
    except IndexError as e:
        print(f"IndexError caught: {e}")
    
    # 5. KeyError: Occurs when a dictionary doesn't have the requested key.
    user = {"name": "Asabeneh", "age": 250}
    try:
        print(user["country"])
    except KeyError as e:
        print(f"KeyError caught: Key {e} not found")
    
    # 6. AttributeError: Occurs when an invalid attribute/method is called.
    import math
    try:
        # math has 'sqrt', but not 'square_root'
        math.square_root(25)
    except AttributeError as e:
        print(f"AttributeError caught: {e}")
    
    # 7. ZeroDivisionError: Occurs when dividing by zero.
    try:
        division = 10 / 0
    except ZeroDivisionError as e:
        print(f"ZeroDivisionError caught: {e}")
```

## Execution Steps

1. Install Python: Ensure you have Python installed on your machine.

2. Create the file: Open your text editor (VS Code, Sublime, etc.) and create a new file named **day15.py**.

3. Copy the code: Copy the code block above and paste it into the file.

4. Run the script: Open your terminal or command prompt and navigate to the folder where the file is saved. Type:

```shell
    python day15.py
```
5. Observe: Note how we used **try...except** blocks. This allows the script to continue running even after an error occurs. Without these blocks, the program would stop at the very first error!

## Mini Challenge

**Goal:** Write a small script that intentionally triggers three different error types and prints a custom message for each.

1. Create a list of 3 items and try to print the 10th item.

2. Try to convert a string that contains letters (e.g., "Apple") into an integer using **int()**. (This will trigger a **ValueError**).

3. Try to multiply a string by another string.

**Checklist:**

* [ ] Did you identify which error type each action caused?

* [ ] Did you use try...except to keep your program from crashing?

# 📘 Day 16: Python Date Time

Python doesn't have a data type called "date" of its own, but we can import a module named **datetime** to work with dates as objects. These objects allow us to manipulate years, months, days, hours, and even microseconds with ease.

## Key Concepts

Today, we will cover the following:

* Importing the **datetime** module.

* Getting the current date and time.

* Creating specific date objects.

* Formatting dates into readable strings using **strftime**.

* Parsing strings into date objects using **strptime.**

* Calculating time differences using **timedelta.**

## Code Examples

```shell
    import datetime
    
    # --- 1. Getting Current Date and Time ---
    now = datetime.datetime.now()
    print(f"Current Date and Time: {now}")
    print(f"Current Year: {now.year}")
    print(f"Current Month: {now.month}")
    
    # --- 2. Creating a Specific Date ---
    # Syntax: datetime.datetime(year, month, day, hour, minute, second)
    target_date = datetime.datetime(2025, 1, 1, 12, 0, 0)
    print(f"Target Date: {target_date}")
    
    # --- 3. Formatting Dates (strftime) ---
    # %Y = Year, %m = Month, %d = Day, %H = Hour, %M = Minute
    readable_date = now.strftime("%B %d, %Y")
    print(f"Formated Date: {readable_date}")
    
    # --- 4. Converting String to Date (strptime) ---
    date_string = "25 December, 2023"
    parsed_date = datetime.datetime.strptime(date_string, "%d %B, %Y")
    print(f"Parsed Object: {parsed_date}")
    
    # --- 5. Using Timedelta for Calculations ---
    # Let's find out what the date will be in 10 days
    today = datetime.date.today()
    ten_days_later = today + datetime.timedelta(days=10)
    print(f"Date in 10 days: {ten_days_later}")
    
    # Calculate difference between two dates
    diff = target_date - now
    print(f"Days until target: {diff.days} days")
```

## Execution Steps

To run the code above, follow these simple steps:

1. Open your editor: Open VS Code, PyCharm, or any text editor.

2. Create a file: Create a new file and name it **day16.py**.

3. Copy and Paste: Copy the code block provided above and paste it into your file.

4. Run the script: Open your terminal or command prompt and type:
```shell
    python day16.py
```
5. Observe: Check the output to see how Python displays the date objects versus the formatted strings.

## Mini Challenge: "The Birthday Calculator"

Now it's your turn! Write a script that does the following:

1. Store your birthday in a variable using the **datetime** object.

2. Calculate how many days are left until your **next** birthday.

3. Print the result in a friendly message (e.g., "Only 45 days left until my birthday!").

**Pro Tip:** Use **datetime.date.today()** to get today's date and compare it with your birthday month and day.

# 📘 Day 17: Exception Handling

In Python, an **exception** is an error that happens during the execution of a program. When a Python script encounters a situation it cannot cope with, it raises an exception. If we don’t handle it, the program crashes.

**Exception Handling** is the process of anticipating these errors and providing a graceful way for the program to continue running or inform the user politely, rather than just quitting with a scary error message.

## Key Concepts

In this lesson, we will cover the four blocks used to handle exceptions:

* **`try`:** The block of code where you anticipate an error might occur.

* **`except`:** The block that executes if an error occurs in the **try** block.

* **`else`:** (Optional) The block that runs only if no errors were raised.

* **`finally`:** (Optional) The block that runs no matter what happens (great for cleanup tasks).

* **Specific Exceptions:** How to catch specific errors like **ValueError** or **ZeroDivisionError**.

## Code Examples

#### Basic Exception Handling
This example demonstrates how to prevent a program from crashing when a user provides invalid input.

```shell
    # Day 17: Exception Handling Example
    
    def divide_numbers():
        try:
            # Prompt user for input
            numerator = int(input("Enter a number to divide: "))
            denominator = int(input("Enter a number to divide by: "))
            
            # This will raise ZeroDivisionError if denominator is 0
            # or ValueError if input is not an integer
            result = numerator / denominator
            
        except ValueError:
            # Runs if the user types something that isn't an integer
            print("Error: Please enter valid whole numbers.")
            
        except ZeroDivisionError:
            # Runs if the user tries to divide by zero
            print("Error: You cannot divide by zero!")
            
        except Exception as e:
            # Catch-all for any other unexpected errors
            print(f"An unexpected error occurred: {e}")
            
        else:
            # Runs only if the try block was successful
            print(f"Success! The result is: {result}")
            
        finally:
            # Runs every single time, regardless of errors
            print("Thank you for using the divider program.")
    
    # Execute the function
    divide_numbers()
```

#### Handling File Errors
It is very common to use exception handling when working with files.

```shell
    try:
        # Attempt to open a file that might not exist
        with open("secret_data.txt", "r") as file:
            content = file.read()
            print(content)
    except FileNotFoundError:
        print("Oops! The file 'secret_data.txt' was not found.")
```

## Execution Steps

To run these examples:

1. Open your IDE: Open VS Code, PyCharm, or any text editor.

2. Create a file: Save the code as **day17.py**.

3. Run the script: Open your terminal or command prompt and type:
```shell
    python day17.py
```
4. Test it: Run the script multiple times. Try entering a string (like "hello") instead of a number, or try dividing by zero to see how the program responds without crashing.

## Mini Challenge: The "Age Calculator"

Write a small script that asks a user for their **year of birth** and calculates their age.

**Requirements:**

1. Use a **try** block to convert the user input to an integer.

2. Use an **except** block to catch **ValueError** if the user types something other than a number.

3. Add a **finally** block that prints "Calculation complete."

**Example Logic:**

* Input: **1995** -> Output: **You are 29 years old.**

* Input: **banana** -> Output: **That is not a valid year!**

*Hint: Use 2026 (or the current year) as the base for your subtraction.*

# 📘 Day 18: Regular Expressions in Python

A Regular Expression is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern. Think of it as a "Super Search" tool. While a standard search looks for an exact word, RegEx allows you to search for patterns, such as "any email address," "any phone number," or "any word that starts with 'A' and ends with 'z'."

In Python, we use the built-in **`re`** module to work with regular expressions.

## Key Concepts

In this lesson, we will cover:

* **The `re` module:** Importing and using the library.

* **Common Functions:** **re.match()**, **re.search()**, **re.findall()**, and **re.split()**.

* **Meta-characters:** Characters with special meanings **(e.g., . , ^, $, *, +)**.

* **Character Sets:** Using **[]** to match specific types of characters.

* **Quantifiers:** Specifying how many times a character should repeat.

## Code Examples

Let's explore how to use the `re` module with practical examples.

```shell
    import re
    
    # Sample text for our demonstrations
    text = "Python is amazing. I love learning Python in 2024!"
    
    # 1. re.findall() - Finds all occurrences of a pattern
    # Let's find every instance of 'Python'
    matches = re.findall(r"Python", text)
    print(f"Findall matches: {matches}")  # Output: ['Python', 'Python']
    
    # 2. re.search() - Searches for a pattern and returns a Match object (first occurrence)
    search_obj = re.search(r"amazing", text)
    if search_obj:
        print(f"Match found at index: {search_obj.start()}")
    else:
        print("No match found.")
    
    # 3. Using Meta-characters
    # \d matches any digit (0-9)
    # + means 'one or more'
    digits = re.findall(r"\d+", text)
    print(f"Digits found: {digits}")  # Output: ['2024']
    
    # 4. Character Sets []
    # Let's find words that start with 'l' or 'a'
    # \b represents a word boundary
    words = re.findall(r"\b[la]\w+", text)
    print(f"Words starting with 'l' or 'a': {words}") # Output: ['love', 'learning', 'amazing']
    
    # 5. re.sub() - Replace patterns
    # Replace 'Python' with 'Coding'
    new_text = re.sub(r"Python", "Coding", text)
    print(f"Replaced text: {new_text}")
```

## Execution Steps

To see these examples in action, follow these steps:

1. Open your Editor: Open your favorite code editor (VS Code, PyCharm, or even a simple text editor).

2. Create the File: Create a new file named **day18.py**.

3. Copy and Paste: Copy the code block provided in the "Code Examples" section above and paste it into your file.

4. Run the Script: Open your terminal or command prompt and navigate to the folder where you saved the file. Run it using:
```shell
    python day18.py
```
5. Observe: Check the output in your terminal to see how the patterns matched the text!

## Mini Challenge: The Email Validator

Now it's your turn! Write a small script that checks if a string is a valid email format.

**Requirements:**

1. Import the `re` module.

2. Define a string called **`email`**.

3. Create a pattern that checks for:

* One or more alphanumeric characters.

* An **`@`** symbol.

* One or more alphanumeric characters.

* A dot `.` followed by 2 to 4 letters (like `.com` or `.org`).

4. Use **`re.match()`** to see if the email matches your pattern.

**Hint:**

A basic pattern to start with is: **`r"^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$"`**
