# 🧮 Smart CLI Calculator with OOP and Advanced Math

An object-oriented, interactive calculator program in Python, built to support both **basic** and **advanced mathematical operations** with custom function mapping, user input handling, and dynamic extensibility.

This project was developed as part of a Data Science study assignment to reinforce Python's OOP principles and practical use of external libraries like `math`.

---

## 📌 Project Description

This calculator expands on the typical `+ - * /` operations by introducing:

- Object-Oriented Design (OOP)
- Function mapping with a dictionary
- User-defined operation extension
- Advanced math operations like:
  - Exponentiation
  - Square Root
  - Logarithm (base 10)
- Error handling and input validation using `isinstance()`

Users can continue using the calculator until they decide to exit via terminal input.

---

## 🧠 Learning Objectives

This project demonstrates practical understanding of:

- Python Classes and Methods
- Using dictionaries to map symbols to functions
- Adding new operations dynamically
- Input validation and error handling
- Interactive CLI logic with `while` loops
- Using Python’s `math` library

---


---

## 🚀 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/Richart-d/oop-advanced-calculator-python.git
cd oop-advanced-calculator-python

⚙️ Features
✅ Basic operations: +, -, *, /

🧠 Advanced operations: **, sqrt, log

🔧 Add new operations using add_operation()

🛡️ Error handling for invalid inputs and operations

🔄 Loop to perform multiple calculations

📐 Sample Usage
# Inside calculator.py

calc = Calculator()

# Basic usage
calc.calculate(5, "+", 3)       # Output: 8

# Add exponentiation
calc.add_operation("**", lambda x, y: x ** y)
calc.calculate(2, "**", 3)      # Output: 8

# Error check
calc.calculate("two", "+", 3)   # Raises error for invalid input


🧩 Potential Future Features
Add support for parentheses and operator precedence
Store and recall previous results
GUI interface using Tkinter or Streamlit
History of calculations


👨‍💻 Author
Richard
Data Science Learner | Python Developer
Built during a Data Science Bootcamp




