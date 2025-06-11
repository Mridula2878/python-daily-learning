# 🐍 Python Daily Learning

Welcome to my journey of learning Python — one day at a time!

This repository holds Jupyter notebooks documenting my progress as I explore Python, starting from the very basics.

---

## 📅 Progress Overview

| Day | Topic Covered                                                                                                                                              | Notebook File                      |
|-----|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| 1   | My First Python Program – Hello World                                                                                                                     | `Day1_HelloWorld.ipynb`            |
| 2   | Basic Python Syntax, Data Types (int, float, str), Variables                                                                                               | `Day2_Syntax_DataTypes.ipynb`      |
| 3   | Control Structures – `if`, `else`, `elif`                                                                                                                  | `Day3_ControlStructures_IfElse.ipynb` |
| 4   | Control Structures – `for` Loops                                                                                                                           | `Day4_ForLoops.ipynb`              |
| 5   | Working with Lists – Creating, Accessing, Slicing, Modifying, Adding, Removing, Deleting, Clearing, Checking, Length, and List Comprehension              | `Day5_Lists.ipynb`                 |
## 🧁 Day 8 - Cupcake Function Practice

Today I learned how to:
- Create and call functions in Python
- Use `if` and `else` conditions
- Understand indentation (how to organize code blocks)
- Build a fun function that prints cupcake messages based on size, flavor, and sprinkles

### 🧪 Example Code:
```python
def make_cupcake(size, flavor, sprinkles):
    message = "Here is your " + size + " " + flavor + " cupcake!"
    if sprinkles == "yes":
        message += " Sprinkles included!"
    print(message)

make_cupcake("small", "chocolate", "yes")
