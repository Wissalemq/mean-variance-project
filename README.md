# Mean-Variance-Standard Deviation Calculator

This project is a Python function that calculates statistical values from a 3x3 matrix using NumPy.

## 📌 Features
The function returns:
- Mean
- Variance
- Standard Deviation
- Maximum
- Minimum
- Sum

All calculations are performed:
- Across columns (axis=0)
- Across rows (axis=1)
- Across the entire matrix

## 🧠 How it works
- The input is a list of 9 numbers
- The list is converted into a 3x3 NumPy array
- Statistical operations are applied using NumPy functions

## ⚠️ Error Handling
If the list does not contain exactly 9 numbers, the function raises:
