**Python Course**

**Introduction to Python**
Python is a versatile and widely-used programming language known for its simplicity and readability. It is used in web development, data science, artificial intelligence, automation, and more.

### **Module 1: Python Basics**
1. **Introduction to Python**
   - **What is Python?**
     - Python is a high-level, interpreted programming language designed for code readability and ease of use.
   - **History and Evolution**
     - Created by Guido van Rossum in 1991, Python has evolved into one of the most popular programming languages.
   - **Setting up Python**
     - Download and install Python from [official website](https://www.python.org/).
     - Verify installation using:
       ```bash
       python --version
       ```
   - **Running Python Programs**
     - You can write Python scripts (`.py` files) and run them using:
       ```bash
       python script.py
       ```

2. **Variables and Data Types**
   - **Declaring Variables**
     ```python
     x = 10  # Integer
     y = 3.14  # Float
     name = "Alice"  # String
     is_active = True  # Boolean
     ```
   - **Type Conversion**
     ```python
     num = "100"
     num_int = int(num)
     print(num_int, type(num_int))  # Output: 100 <class 'int'>
     ```

3. **Operators and Expressions**
   - **Arithmetic Operators**
     ```python
     a = 10
     b = 5
     print(a + b, a - b, a * b, a / b, a % b, a ** b)
     ```

### **Module 2: Control Flow**
1. **Conditional Statements**
   ```python
   age = 18
   if age >= 18:
       print("Adult")
   elif age == 17:
       print("Almost an adult")
   else:
       print("Minor")
   ```

2. **Loops**
   - **For Loop**
     ```python
     for i in range(5):
         print(i)
     ```
   - **While Loop**
     ```python
     x = 0
     while x < 5:
         print(x)
         x += 1
     ```

### **Module 3: Functions and Modules**
1. **Defining and Calling Functions**
   ```python
   def greet(name):
       return f"Hello, {name}!"
   print(greet("Alice"))
   ```

2. **Modules and Packages**
   ```python
   import math
   print(math.sqrt(16))  # 4.0
   ```

### **Module 4: Data Structures**
1. **Lists**
   ```python
   fruits = ["apple", "banana", "cherry"]
   fruits.append("orange")
   print(fruits)
   ```

2. **Dictionaries**
   ```python
   person = {"name": "Alice", "age": 25}
   print(person["name"])
   ```

### **Module 5: Object-Oriented Programming (OOP)**
1. **Classes and Objects**
   ```python
   class Person:
       def __init__(self, name, age):
           self.name = name
           self.age = age
   
   p1 = Person("Alice", 25)
   print(p1.name)
   ```

### **Module 6: File Handling**
1. **Reading and Writing Files**
   ```python
   with open("file.txt", "w") as f:
       f.write("Hello, Python!")
   with open("file.txt", "r") as f:
       print(f.read())
   ```

### **Module 7: Exception Handling**
1. **Try, Except, Finally**
   ```python
   try:
       x = 1 / 0
   except ZeroDivisionError:
       print("Cannot divide by zero")
   finally:
       print("Execution completed")
   ```

### **Module 8: Advanced Python Concepts**
1. **Decorators**
   ```python
   def decorator(func):
       def wrapper():
           print("Before function call")
           func()
           print("After function call")
       return wrapper
   
   @decorator
   def say_hello():
       print("Hello!")
   
   say_hello()
   ```

### **Module 9: Database Handling**
1. **SQLite with Python**
   ```python
   import sqlite3
   conn = sqlite3.connect("test.db")
   cursor = conn.cursor()
   cursor.execute("CREATE TABLE IF NOT EXISTS users (id INTEGER, name TEXT)")
   conn.commit()
   conn.close()
   ```

### **Module 10: Web Scraping**
1. **Using BeautifulSoup**
   ```python
   from bs4 import BeautifulSoup
   import requests
   
   url = "https://example.com"
   page = requests.get(url)
   soup = BeautifulSoup(page.content, "html.parser")
   print(soup.title.text)
   ```

### **Module 11: GUI Programming**
1. **Tkinter Basics**
   ```python
   from tkinter import Tk, Label
   
   root = Tk()
   label = Label(root, text="Hello, Tkinter!")
   label.pack()
   root.mainloop()
   ```

### **Module 12: Data Science with Python**
1. **Using Pandas and NumPy**
   ```python
   import pandas as pd
   import numpy as np
   
   data = pd.DataFrame(np.random.rand(5, 3), columns=["A", "B", "C"])
   print(data)
   ```

### **Module 13: Web Development with Python**
1. **Flask Basics**
   ```python
   from flask import Flask
   app = Flask(__name__)
   
   @app.route("/")
   def home():
       return "Hello, Flask!"
   
   if __name__ == "__main__":
       app.run()
   ```

### **Module 14: Machine Learning with Python**
1. **Using Scikit-Learn**
   ```python
   from sklearn.linear_model import LinearRegression
   import numpy as np
   
   X = np.array([[1], [2], [3], [4]])
   y = np.array([2, 4, 6, 8])
   model = LinearRegression()
   model.fit(X, y)
   print(model.predict([[5]]))  # Output: [10.]
   ```

### **Module 15: Automation and Scripting**
1. **Using Python for Automation**
   ```python
   import os
   os.system("echo Hello, World!")
   ```

This course now explains each topic in detail with examples. Let me know if you need further enhancements!

