# NumPy Introduction - A Comprehensive Tutorial

This Jupyter notebook provides a comprehensive introduction to NumPy (Numerical Python), a fundamental library for scientific computing in Python. It covers everything from basic array operations to advanced concepts like reshaping, aggregation, and practical applications.

## 📋 Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Notebook Structure](#notebook-structure)
  - [1. Installation and Setup](#1-installation-and-setup)
  - [2. NumPy Data Types and Attributes](#2-numpy-data-types-and-attributes)
  - [3. Creating Arrays](#3-creating-arrays)
  - [4. Viewing and Manipulating Arrays](#4-viewing-and-manipulating-arrays)
  - [5. Array Operations and Comparisons](#5-array-operations-and-comparisons)
  - [6. Aggregation Functions](#6-aggregation-functions)
  - [7. Reshaping and Transposing](#7-reshaping-and-transposing)
  - [8. Dot Product and Matrix Multiplication](#8-dot-product-and-matrix-multiplication)
  - [9. Practical Example: Nut Butter Sales Analysis](#9-practical-example-nut-butter-sales-analysis)
  - [10. Comparison Operators](#10-comparison-operators)
  - [11. Sorting Arrays](#11-sorting-arrays)
  - [12. Image Processing with NumPy](#12-image-processing-with-numpy)

## 🎯 Overview
This tutorial introduces the core concepts of NumPy, including:
- Creating and manipulating multi-dimensional arrays (ndarrays)
- Understanding array attributes (shape, size, dtype, ndim)
- Performing element-wise operations
- Aggregation functions (sum, mean, std, var)
- Reshaping and transposing arrays
- Dot products and matrix multiplication
- Practical data analysis examples
- Image processing with NumPy arrays

## 📚 Prerequisites
- Python 3.x installed
- Basic understanding of Python programming
- Jupyter Notebook or JupyterLab environment

## 📖 Notebook Structure

### 1. Installation and Setup
```python
pip install numpy
import numpy as np
```

### 2. NumPy Data Types and Attributes
Learn about the main NumPy data type - **ndarray** (n-dimensional array):
- Creating 1D, 2D, and 3D arrays
- Understanding array attributes:
  - `.shape` - dimensions of the array
  - `.ndim` - number of dimensions
  - `.dtype` - data type of elements
  - `.size` - total number of elements

### 3. Creating Arrays
Various methods to create NumPy arrays:
- `np.array()` - from Python lists
- `np.ones()` - arrays filled with ones
- `np.arange()` - arrays with evenly spaced values
- `np.random.randint()` - random integer arrays
- `np.random.random()` - random float arrays
- `np.random.seed()` - reproducible random numbers

### 4. Viewing and Manipulating Arrays
Techniques for accessing and modifying array elements:
- Slicing arrays with indices
- Viewing multi-dimensional array structures

### 5. Array Operations and Comparisons
Perform element-wise operations:
- Addition, subtraction, multiplication, division
- Floor division
- Power operations
- Mathematical functions: `np.exp()`, `np.log()`, `np.square()`

### 6. Aggregation Functions
Compute statistics across arrays:
- `np.sum()` - sum of all elements
- `np.mean()` - arithmetic mean
- `np.max()` - maximum value
- `np.std()` - standard deviation
- `np.var()` - variance
- Performance comparison between Python `sum()` and NumPy `np.sum()`

### 7. Reshaping and Transposing
Transform array shapes:
- `.reshape()` - change array dimensions
- `.T` - transpose arrays
- Understanding broadcasting

### 8. Dot Product and Matrix Multiplication
Matrix operations:
- Element-wise multiplication (Hadamard product)
- `np.dot()` - matrix multiplication
- Transposing for compatibility

### 9. Practical Example: Nut Butter Sales Analysis
A real-world example demonstrating:
- Creating sales data arrays
- Computing total revenue using dot product
- Converting between NumPy arrays and Pandas DataFrames

### 10. Comparison Operators
Element-wise comparisons:
- `>` - greater than
- `>=` - greater than or equal to
- `==` - equal to
- Boolean arrays from comparisons

### 11. Sorting Arrays
Sorting techniques:
- `np.sort()` - sorted array
- `np.argsort()` - indices that would sort the array
- `np.argmin()` - index of minimum value
- `np.argmax()` - index of maximum value

### 12. Image Processing with NumPy
- Loading images as NumPy arrays using `matplotlib.image.imread()`
- Understanding image array structure (height, width, RGB channels)
- Viewing image data as arrays

## 🚀 Key Learning Outcomes
After completing this notebook, you will be able to:
1. Create and manipulate NumPy arrays of any dimension
2. Perform mathematical operations efficiently using vectorized operations
3. Apply aggregation functions for data analysis
4. Reshape and transpose arrays for different applications
5. Compute dot products for linear algebra operations
6. Process and analyze image data
7. Compare Python and NumPy performance for computational tasks

## 📊 Data Analysis Example
The notebook includes a practical sales analysis example:
- Weekly sales data for almond butter, peanut butter, and cashew butter
- Price arrays for each product
- Total revenue calculation using dot product
- Data visualization with Pandas DataFrames

## 🖼️ Image Processing Examples
- Loading and displaying images
- Exploring image array dimensions and data types
- Understanding RGB color representation in NumPy arrays

## 🔧 Requirements
```
numpy
pandas
matplotlib
IPython
```

## 💡 Tips for Working with NumPy
- Use vectorized operations instead of loops for better performance
- Leverage broadcasting for operations between arrays of different shapes
- Understand memory layout with `C` and `F` ordering for efficient operations
- Use built-in aggregation functions instead of writing custom loops

## 📝 Notes
- The notebook includes performance timing comparisons between Python and NumPy operations
- Real-world example demonstrates practical application of dot product
- Image processing section shows how images are represented as multi-dimensional arrays

## 👥 Contributing
Feel free to experiment with the code examples and modify them to explore additional NumPy functionality.

## 📄 License
This tutorial is for educational purposes and can be freely used for learning NumPy and scientific computing in Python.
