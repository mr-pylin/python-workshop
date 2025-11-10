# 🐍 Python Workshop

[![License](https://img.shields.io/github/license/mr-pylin/python-workshop?color=blue)](https://github.com/mr-pylin/python-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.14.0-yellow?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3140/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/c727d7eddc9e42b680c269ab50d628a9)](https://app.codacy.com/gh/mr-pylin/python-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/python-workshop?color=lightblue)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/python-workshop?color=orange)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?color=brightgreen)](https://github.com/mr-pylin/python-workshop/pulls)

Comprehensive **Python** Workshop: **Mastering** Fundamentals and Advanced Techniques.

## 📖 Table of Contents

### 📖 Main Notebooks

1. [**Introduction to Python**](./code/01-introduction-to-python.ipynb)
1. [**Data Structures**](./code/02-data-structures.ipynb)
1. [**Index and Slice**](./code/03-index-&-slice.ipynb)
1. [**Operators and Operands**](./code/04-operator-&-operand.ipynb)
1. [**Type Conversions**](./code/05-type-conversion.ipynb)
1. [**Conditional Statements**](./code/06-conditional-statements.ipynb)
1. [**Loops**](./code/07-loops.ipynb)
1. [**Functions**](./code/08-functions.ipynb)
1. [**Built-In Functions**](./code/09-built-in-functions.ipynb)
1. [**Namespaces and Scopes**](./code/10-namespace-&-scope.ipynb)
1. [**Anonymous Functions (Lambda)**](./code/11-anonymous-functions.ipynb)
1. [**Pack and Unpack Data**](./code/12-pack-unpack.ipynb)
1. [**Type Hints and Docstrings**](./code/13-type-hints-and-docstrings.ipynb)
1. [**Dependencies**](./code/14-dependencies.ipynb)
1. [**Comprehensions**](./code/15-comprehensions.ipynb)
1. [**Introduction to Object-Oriented Programming (OOP)**](./code/16-introduction-to-oop.ipynb)
1. [**Closures and Decorators**](./code/17-closure-decorator.ipynb)
1. [**Object-Oriented Programming Concepts**](./code/18-oop-concepts.ipynb)
1. [**Context Managers**](./code/19-context-managers.ipynb)
1. [**Special Methods**](./code/20-special-methods.ipynb)
1. [**Errors and Exceptions**](./code/21-errors-and-exceptions.ipynb)
1. [**Meta Classes**](./code/22-meta-classes.ipynb)
1. [**Singleton Design**](./code/23-singleton-design.ipynb)

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

This project requires Python **v3.10** or higher. It was developed and tested using Python **v3.12.8**. If you encounter issues, consider using this specific Python version.

### 📝 List of Dependencies

Installing `matplotlib`, `numpy`, `pandas`, and `torch` is **OPTIONAL**. They are used exclusively in the [**Dependencies Notebook**](./code/14-dependencies.ipynb) to demonstrate how to import and manage dependencies effectively.

[![ipykernel](https://img.shields.io/badge/ipykernel-7.0.1-ff69b4)](https://pypi.org/project/ipykernel/7.0.1/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.10.7-green)](https://pypi.org/project/matplotlib/3.10.7/)
[![numpy](https://img.shields.io/badge/numpy-2.3.4-orange)](https://pypi.org/project/numpy/2.3.4/)
[![pandas](https://img.shields.io/badge/pandas-2.3.3-yellow)](https://pypi.org/project/pandas/2.3.3/)
[![torch](https://img.shields.io/badge/torch-2.9.0-gold)](https://pytorch.org/)

### 📦 Install Dependencies

#### 📦 Method 1: uv (**Recommended** ✅)

- Use [**uv**](https://docs.astral.sh/uv/) for dependency management. It handles dependencies, virtual environments, and locking versions more efficiently than pip.  
- To install exact dependency versions specified in [**uv.lock**](./uv.lock) for consistent environments **without** installing the current project as a package:

  ```bash
    uv sync --no-install-project                   # Install only numpy
    uv sync --no-install-project --extra complete  # Install numpy + optional dependencies
  ```

#### 📦 Method 2: Pip

- Install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

  ```bash
  pip install -r requirements.txt
  ```

- **Note**: The [**requirements.txt**](./requirements.txt) includes complete installation of dependencies. Comment `matplotlib`, `numpy`, `pandas`, and `torch` in order to skip [**Dependencies**](./code/14-dependencies.ipynb) section`.

### 🛠️ Usage Instructions

1. Open the root folder with [**VS Code**](https://code.visualstudio.com/) (`Ctrl/Cmd + K` followed by `Ctrl/Cmd + O`).
1. Open `.ipynb` files using the [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**.
1. Select the correct Python kernel and virtual environment where the dependencies were installed.
1. Allow **VS Code** to install any recommended dependencies for working with Jupyter Notebooks.

✍️ **Notes**:  

- It is **highly recommended** to stick with the exact dependency versions specified in [**uv.lock**](./uv.lock) or [**requirements.txt**](./requirements.txt) rather than using the latest package versions. The repository has been **tested** on these versions to ensure **compatibility** and **stability**.
- This repository is **actively maintained**, and dependencies are **updated regularly** to the latest **stable** versions.
- The **table of contents** embedded in the **notebooks** may not function correctly on **GitHub**.
- For an improved experience, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/python-workshop).

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
  - My NumPy Workshop: [**github.com/mr-pylin/numpy-workshop**](https://github.com/mr-pylin/numpy-workshop)
- **Pandas**
  - A powerful, open-source data analysis and manipulation library for Python.
  - Official site: [pandas.pydata.org](https://pandas.pydata.org/)
  - My Pandas Workshop: [**github.com/mr-pylin/pandas-workshop**](https://github.com/mr-pylin/pandas-workshop)
- **Data Visualization**
  - A comprehensive collection of Python libraries for creating static, animated, and interactive visualizations: **Matplotlib**, **Seaborn**, and **Plotly**.
  - Official sites: [matplotlib.org](https://matplotlib.org/) | [seaborn.pydata.org](https://seaborn.pydata.org/) | [plotly.com](https://plotly.com/)
  - My Data Visualization Workshop: [**github.com/mr-pylin/data-visualization-workshop**](https://github.com/mr-pylin/data-visualization-workshop)
- **PyTorch**
  - An open-source **machine learning** library for Python developed by [**Meta AI**](https://ai.meta.com/), used for applications such as **deep learning** and **neural networks**.
  - Official site: [pytorch.org](https://pytorch.org/)
  - My PyTorch Workshop: [**github.com/mr-pylin/pytorch-workshop**](https://github.com/mr-pylin/pytorch-workshop)
- **Media Processing**
  - A comprehensive resource to explore media processing, from fundamental concepts to advanced techniques.
  - Official sites: [opencv.org](https://opencv.org/) | [scikit-image.org](https://scikit-image.org/) | [scipy.org](https://scipy.org/)
  - My Media Processing Workshop: [**github.com/mr-pylin/media-processing-workshop**](https://github.com/mr-pylin/media-processing-workshop)

## 🔍 Find Me

Any mistakes, suggestions, or contributions? Feel free to reach out to me at:

- 📍[**linktr.ee/mr_pylin**](https://linktr.ee/mr_pylin)

I look forward to connecting with you! 🏃‍♂️

## 📄 License

This project is licensed under the **[Apache License 2.0](./LICENSE)**.  
You are free to **use**, **modify**, and **distribute** this code, but you **must** include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./NOTICE) files in any distribution of your work.

### ©️ Copyright Information

- **Original Images**:
  - The images located in the [**./assets/images/original/**](./assets/images/original/) folder are licensed under the **[CC BY-ND 4.0](./assets/images/original/LICENSE)**.
  - The images located in the [**assets/images/python/**](./assets/images/python/) folder are sourced from the [**Python Software Foundation**](https://www.python.org/community/logos/) and are protected under the [**PSF Trademark Usage Policy**](https://www.python.org/psf/trademarks/).
