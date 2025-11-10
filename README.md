# 🐼 Pandas Fundamentals

A learning-driven repository documenting my journey through **Pandas fundamentals**.  
Each problem solution demonstrates structured problem-solving, data-manipulation expertise, and clarity in implementation.

---

## 📘 Overview
This repository contains solutions to **15 core exercises** from the *Introduction to Pandas* course.  
It showcases how to work efficiently with tabular data using Python and the Pandas library.

---

## 🧩 Topics Covered
- Creating and manipulating **DataFrames**
- Selecting and filtering data
- Sorting, grouping, and aggregating
- Adding and transforming columns
- Cleaning and inspecting datasets

---

## 💻 Example Code
```python
import pandas as pd

def findHeavyAnimals(animals: pd.DataFrame) -> pd.DataFrame:
    return animals[animals['weight'] > 100].sort_values('weight', ascending=False)[['name']]
