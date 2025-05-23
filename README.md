Welcome to my Python practice repository!

This space contains beginner-friendly notebooks and mini-projects I’ve created as part of my data science journey with Axia Africa
using Google Colab on mobile (without a laptop).

## What have I done here?

File                        Description                                                
`calculator_if_exit.ipynb`  - One-time calculator using (if/elif/else)logic and fixed test values
`calculator_with_loop.ipynb` - Loop-based calculator that simulates multiple operations and exits 
`Onphonepractice.ipynb` -  My earliest mobile Python practice notebook – variables, strings, loops
`PythonL2.ipynb` -   Python basics continued – functions, dictionaries, operators 
`PythonLibraries.ipynb` - Notes and tests on Python libraries: NumPy, Pandas (intro level)
`Data_Visualization.ipynb` - Beginner-level data plotting with Matplotlib and Seaborn

Calculator Project (Mini Highlight)

I created two versions of a calculator to learn how Python handles logic and flow control.

## 1. `calculator_if_exit.ipynb`
Single-run calculator using conditionals
Built with hardcoded values(no input, for mobile compatibility)
Work an exit option with option `8`

## 2. `calculator_with_loop.ipynb`
Uses a (for) loop and a list of test cases
Simulates multiple operations in one run
Exits with a break when (opt == 8)
  
**Practiced:**  
Functions, conditional logic, loops, error handling (division by zero), clean code writing.

##Why I Used Fixed Values

Because `input()` doesn't work on Google Colab mobile, I worked an user input using:
- test_caseslist (for the loop version)
- Hardcoded variables (for the one-time version)
This allowed me to still learn real logic structures while using a phone.

### Skills Covered So Far
Python syntax & indentation  
Variables and data types  
String formatting  
Lists, Tuples, Sets, and Dictionaries  
Conditional statements  
Loops (`for`, `while`, `break`)  
Functions and return values  
Basic error handling  
NumPy basics (arrays, indexing)  
Pandas basics (Series, DataFrames)  
Matplotlib & Seaborn basics for data visualization 

## What's more to do?
Create an interactive version using input() (once I have laptop access)
Build a menu-driven calculator that runs in a true `while True` loop
Add more operations: modulus `%`, power `**`, square roots
Convert the logic into a simple command-line app in the future.
