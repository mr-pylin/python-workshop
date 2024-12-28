# 🐍 Python Workshop

[![License](https://img.shields.io/github/license/mr-pylin/python-workshop)](https://github.com/mr-pylin/python-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.12.3-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3123/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/c727d7eddc9e42b680c269ab50d628a9)](https://app.codacy.com/gh/mr-pylin/python-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Code Style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/python-workshop)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/python-workshop)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/mr-pylin/python-workshop/pulls)

Comprehensive **Python** Workshop: **Mastering** Fundamentals and Advanced Techniques.

## 📖 Table of Contents

### 📖 Main Notebooks

1. [**Introduction to Python**](./code/01-introduction-to-python.ipynb)  
A beginner-friendly introduction to Python, its features, and basic syntax.
1. [**Data Structures**](./code/02-data-structures.ipynb)  
Explore essential data structures like `int`, `float`, `list`, `tuple`, `dictionary`, and `set`.
1. [**Index and Slice**](./code/03-index-&-slice.ipynb)  
Learn how to access and manipulate elements of sequences using indexing and slicing.
1. [**Operators and Operands**](./code/04-operator-&-operand.ipynb)  
Study various operators (arithmetic, comparison, logical, etc.) and how they work with operands.
1. [**Type Conversions**](./code/05-type-conversion.ipynb)  
Understand how to convert data types in Python with explicit and implicit conversions.
1. [**Conditional Statements**](./code/06-conditional-statements.ipynb)  
Learn about `if-elif-else` and `match-case` statements for controlling the flow of your programs.
1. [**Loops**](./code/07-loops.ipynb)  
Master loops (`for`, `while`) to iterate over sequences and perform repeated tasks.
1. [**Functions**](./code/08-functions.ipynb)  
Understand how to define and use functions, including parameters and return values.
1. [**Built-In Functions**](./code/09-built-in-functions.ipynb)  
Explore Python's powerful built-in functions and how to leverage them in your programs.
1. [**Namespaces and Scopes**](./code/10-namespace-&-scope.ipynb)  
Learn about namespaces and scope resolution to avoid name conflicts in your code.
1. [**Anonymous Functions (Lambda)**](./code/11-anonymous-functions.ipynb)  
Discover the usage of `lambda` expressions for creating small, anonymous functions.
1. [**Pack and Unpack Data**](./code/12-pack-unpack.ipynb)  
Learn how to pack multiple values into a variable and unpack them in Python.
1. [**Type Hints and Docstrings**](./code/13-type-hints-and-docstrings.ipynb)  
Understand how to improve code readability with type hints and document your functions with docstrings.
1. [**Dependencies**](./code/14-dependencies.ipynb)  
Learn how to manage and install dependencies using `pip` and `requirements.txt` and use them in your code.
1. [**Comprehensions**](./code/15-comprehensions.ipynb)  
Master `list`, `set`, `dictionary`, and `generator` comprehensions for concise and readable code.
1. [**Introduction to Object-Oriented Programming (OOP)**](./code/16-introduction-to-oop.ipynb)  
Get introduced to the basic concepts of object-oriented programming in Python.
1. [**Closures and Decorators**](./code/17-closure-decorator.ipynb)  
Learn about closures and how to use decorators for enhancing functions.
1. [**Object-Oriented Programming Concepts**](./code/18-oop-concepts.ipynb)  
Explore core OOP concepts such as *encapsulation*, *inheritance*, *polymorphism*, and *abstraction*.
1. [**Context Managers**](./code/19-context-managers.ipynb)  
Learn to manage resources efficiently using `with` statements and defining custom context managers.
1. [**Special Methods**](./code/20-special-methods.ipynb)  
Discover Python's dunder (double underscore) methods for creating custom behavior in your classes.
1. [**Errors and Exceptions**](./code/21-errors-and-exceptions.ipynb)  
Learn about handling errors and exceptions to make your code more robust.
1. [**Meta Classes**](./code/22-meta-classes.ipynb)  
Dive into metaclasses to understand how classes in Python are created and customized.
1. [**Singleton Design**](./code/23-singleton-design.ipynb)  
Understand the Singleton Design Pattern for ensuring a class has only one instance, with examples in Python.

### 📖 Built-in Methods

- [**Numbers Methods**](./code/builtins/list-methods.ipynb)
- [**String Methods**](./code/builtins/string-methods.ipynb)
- [**List Methods**](./code/builtins/list-methods.ipynb)
- [**Tuple Methods**](./code/builtins/tuple-methods.ipynb)
- [**Set Methods**](./code/builtins/set-methods.ipynb)
- [**Dictionary Methods**](./code/builtins/dictionary-methods.ipynb)

## 📋 Prerequisites

- 💻 **Basic Computer Skills**
  - Familiarity with using a computer, web browsers, and file management.
- 🐍 **Python Environment Setup**
  - Ability to set up a Python development environment, including:
    - Installation of Python ([**Anaconda**](https://www.anaconda.com/) or **standalone**).
    - Familiarity with using Integrated Development Environments (IDEs) like [**Jupyter Notebook**](https://jupyter.org/), [**PyCharm**](https://www.jetbrains.com/pycharm/), or [**Visual Studio Code**](https://code.visualstudio.com/).

## ⚙️ Setup

This project requires Python **v3.10** or higher. It was developed and tested using Python **v3.12.3**. If you encounter issues, consider using this specific Python version.

### 📝 List of Dependencies

Installing these dependencies is **OPTIONAL**. They are used exclusively in the [**Dependencies Notebook**](./code/14-dependencies.ipynb) to demonstrate how to import and manage dependencies effectively.

[![matplotlib](https://img.shields.io/badge/matplotlib-3.9.1-green)](https://pypi.org/project/matplotlib/3.9.1/)
[![numpy](https://img.shields.io/badge/numpy-1.26.4-orange)](https://pypi.org/project/numpy/1.26.4/)
[![pandas](https://img.shields.io/badge/pandas-2.2.2-yellow)](https://pypi.org/project/pandas/2.2.2/)
[![torch](https://img.shields.io/badge/torch-2.4.0-yellow)](https://pytorch.org/)

### 📦 Install Dependencies

You can install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

```bash
pip install -r requirements.txt
```

### 🛠️ Usage Instructions

1. Open the root folder with [**VS Code**](https://code.visualstudio.com/):
    - **Windows/Linux**: `Ctrl + K` followed by `Ctrl + O`
    - **macOS**: `Cmd + K` followed by `Cmd + O`
1. Open `.ipynb` files using [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**.
1. Allow **VS Code** to install any **recommended dependencies** for working with Jupyter Notebooks.

✍️ **Notes**:  

- The **table of contents** embedded in the **notebooks** is not fully functional on **GitHub**!
- To navigate the **table of contents** effectively, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/python-workshop) for a better experience.

## 🔗 Useful Links

### **Python**

- Official Website:
  - The main website for Python, offering downloads, news, and community resources.
  - Official site: [python.org](https://www.python.org/)
- Documentation
  - Comprehensive guide and reference for all functionalities and features of the Python programming language.
  - Doc: [docs.python.org](https://docs.python.org/)
- Source Code
  - Over 2500 contributors are currently working on Python.
  - Link: [github.com/python/cpython](https://github.com/python/cpython)

### **Looking Ahead**

- **NumPy**
  - A fundamental package for scientific computing in Python, providing support for **arrays**, **matrices**, and a large collection of **mathematical functions**.
  - Official site: [numpy.org](https://numpy.org/)
  - My NumPy Workshop: [github.com/mr-pylin/numpy-workshop](https://github.com/mr-pylin/numpy-workshop)
- **Pandas**
  - A powerful, open-source data analysis and manipulation library for Python.
  - Official site: [pandas.pydata.org](https://pandas.pydata.org/)
  - My Pandas Workshop: [Coming Soon](https://github.com/mr-pylin/#)
- **Data Visualization**
  - A comprehensive collection of Python libraries for creating static, animated, and interactive visualizations: **Matplotlib**, **Seaborn**, and **Plotly**.
  - Official sites: [matplotlib.org](https://matplotlib.org/) | [seaborn.pydata.org](https://seaborn.pydata.org/) | [plotly.com](https://plotly.com/)
  - My MatPlotLib Workshop: [github.com/mr-pylin/data-visualization-workshop](https://github.com/mr-pylin/data-visualization-workshop)
- **PyTorch**
  - An open-source **machine learning** library for Python developed by [**Meta AI**](https://ai.meta.com/), used for applications such as **deep learning** and **neural networks**.
  - Official site: [pytorch.org](https://pytorch.org/)
  - My PyTorch Workshop: [github.com/mr-pylin/pytorch-workshop](https://github.com/mr-pylin/pytorch-workshop)

## 🔍 Find Me

Any mistakes, suggestions, or contributions? Feel free to reach out to me at:

- 📍[**linktr.ee/mr_pylin**](https://linktr.ee/mr_pylin)

I look forward to connecting with you! 🏃‍♂️

## 📄 License

This project is licensed under the **[Apache License 2.0](./LICENSE)**.  
You are free to use, modify, and distribute this code, but you must include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./NOTICE) files in any distribution of your work.

### ✍️ Additional Licensing Information

- **SVG Images**:
  - The SVG images located in the [./assets/images/svgs/](./assets/images/svgs/) folder are licensed under the **[CC BY-ND 4.0](./assets/images/svgs/LICENSE)**.
  - Note: This license restricts derivative works, meaning you may share these images but cannot modify them.
