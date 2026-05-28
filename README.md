# 📊 Data Analyzer and Transformer

A menu-driven Python program that demonstrates core Python programming concepts through interactive data analysis and transformation operations.

---

## 👤 Author

**Thakkar Disha**

---

## 📌 Overview

This project is a console-based data analysis tool that lets users input numerical datasets and perform a variety of operations — from basic statistics to recursive algorithms and lambda-based filtering. It is structured to cover a broad range of Python fundamentals in a single, cohesive program.

---

## ✨ Features

| Menu Option | Feature |
|---|---|
| 1 | Input 1D data (manual or sample) |
| 2 | Display data summary using built-in functions |
| 3 | Calculate factorial using recursion |
| 4 | Filter data by threshold using lambda + `filter()` / `map()` |
| 5 | Sort data in ascending or descending order |
| 6 | Display full dataset statistics (multiple return values) |
| 7 | Exit the program |

---

## 🧠 Concepts Demonstrated

- **Built-in Functions** — `len()`, `min()`, `max()`, `sum()`
- **User-Defined Functions (UDF)** — `calculate_average()`, `find_duplicates()`, `display_unique_values()`
- **`*args` and `**kwargs`** — flexible argument passing in function definitions
- **`__doc__` strings** — inline documentation for every function
- **Recursion** — `factorial(n)` and `fibonacci(n)`
- **Lambda Functions** — used with `filter()` and `map()`
- **Global Variables** — `dataset_summary` dictionary updated across functions
- **Multiple Return Values** — `get_dataset_statistics()` returns a tuple
- **1D and 2D Lists** — input, display, and manipulation helpers
- **Sorting** — `list.sort()` (in-place) and `sorted()` (non-mutating)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.6 or higher

### Running the Program

```bash
python project-4.py
```

You will be greeted with a main menu. Follow the on-screen prompts to input data and explore each feature.

---

## 💡 Sample Session

```
=======================================================
   Welcome to the Data Analyzer and Transformer Program
=======================================================

Main Menu:
  1. Input Data
  2. Display Data Summary  (Built-in Functions)
  3. Calculate Factorial   (Recursion)
  4. Filter Data by Threshold  (Lambda Function)
  5. Sort Data
  6. Display Dataset Statistics  (Return Multiple Values)
  7. Exit Program

Please enter your choice: 1

Data Input Options:
  1. Enter values manually
  2. Use sample data  [34, 12, 56, 78, 43, 21, 90]
Choose an option: 2
Sample data loaded: [34, 12, 56, 78, 43, 21, 90]
```

---

## 📁 Project Structure

```
project-4.py          # Main program file (all logic and UI)
README.md             # Project documentation
```

---

## 📚 Function Reference

| Function | Description |
|---|---|
| `display_data_summary(data)` | Prints basic stats and updates global summary |
| `calculate_average(data)` | Returns the mean of the dataset |
| `find_duplicates(data)` | Returns a list of duplicate values |
| `display_unique_values(data)` | Prints unique values in the dataset |
| `accept_multiple_values(*args)` | Demonstrates `*args` usage |
| `print_dataset_characteristics(**kwargs)` | Demonstrates `**kwargs` usage |
| `factorial(n)` | Recursively computes n! |
| `fibonacci(n)` | Recursively returns the nth Fibonacci number |
| `filter_by_threshold(data, threshold)` | Filters values using a lambda + `filter()` |
| `double_values(data)` | Doubles each value using a lambda + `map()` |
| `get_dataset_statistics(data)` | Returns (min, max, sum, avg) as a tuple |
| `sort_1d_data(data, ascending)` | In-place sorts a 1D list |
| `sort_2d_rows(data_2d, ascending)` | Sorts each row of a 2D list independently |

---

## 📝 License

This project was created for educational purposes.
