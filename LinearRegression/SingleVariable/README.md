# Linear Regression - Single Variable

This project implements **Linear Regression from scratch** (without scikit-learn).  
We predict **house prices** based on a single feature (e.g., house size).  

---

## 🚀 What I Did
- Implemented the hypothesis function:  
  \[
  f_{w,b}(x) = w \cdot x + b
  \]
- Defined the cost function (Mean Squared Error).  
- Applied **gradient descent** to learn the parameters `w` and `b`.  
- Visualized the cost surface, gradients, and final fitted line.

---

## 📊 Results
- Gradient descent converges to the best-fitting line.  
- Visual plots show how the line improves step by step.  

---

## 🔧 Tech Stack
- Python  
- NumPy  
- Matplotlib  
- Custom helper functions (`lab_utils_uni`)  

---

## 📂 Files
- `linear_regression_univariate.py` → Implementation + visualization
- `dataset.csv` → Training data (house prices vs size)
- `results.png` → Example output plot
