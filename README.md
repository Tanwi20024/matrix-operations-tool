# matrix-operations-tool
An interactive Matrix Operations Tool built with Python &amp; NumPy in Google Colab

# 🧮 Matrix Operations Tool

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-1.x-green?style=flat&logo=numpy)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange?style=flat&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

> **Project 3** of my Python learning journey — An interactive Matrix Operations Tool built using Python and NumPy.

---

## 📌 About the Project

This is a beginner-friendly, interactive **Matrix Operations Tool** built in Python using the **NumPy** library. It allows users to input custom matrices and perform essential mathematical operations through a clean menu-driven interface.

This project was built and run entirely on **Google Colab** — no local setup required!

---

## ✨ Features

- ➕ **Matrix Addition** — Add two matrices of the same dimension
- ➖ **Matrix Subtraction** — Subtract one matrix from another
- ✖️ **Matrix Multiplication** — Dot product of two compatible matrices
- 🔄 **Matrix Transpose** — Flip rows and columns
- 🔢 **Determinant Calculation** — Compute the determinant of a square matrix
- 🛡️ **Error Handling** — Friendly error messages for invalid operations
- 📋 **Interactive Menu** — Clean, numbered menu interface in the console

---

## 🖥️ Demo

```
=============================================
      🧮 MATRIX OPERATIONS TOOL
=============================================

📋 MAIN MENU:
  1. Matrix Addition       (A + B)
  2. Matrix Subtraction    (A - B)
  3. Matrix Multiplication (A × B)
  4. Matrix Transpose      (A or B)
  5. Matrix Determinant    (A or B)
  6. Exit
---------------------------------------------
Enter your choice (1-6): 1

--- Enter Matrix A ---
Enter number of rows: 2
Enter number of columns: 2
  Row 1: 1 2
  Row 2: 3 4

--- Enter Matrix B ---
  Row 1: 5 6
  Row 2: 7 8

=============================================
  ✅ Result of: Addition (A + B)
=============================================
[[ 6.  8.]
 [10. 12.]]
=============================================
```

---

## 🚀 How to Run

### ▶️ Option 1: Google Colab (Recommended for Beginners)

1. Click the badge below to open directly in Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

2. Upload the `matrix_operations.ipynb` file — **File → Upload Notebook**
3. Run each cell top to bottom using **Shift + Enter**
4. The interactive menu will appear in the last cell's output

### 💻 Option 2: Run Locally

**Prerequisites:**
- Python 3.x installed
- NumPy installed

```bash
# Step 1: Clone the repository
git clone https://github.com/YOUR_USERNAME/matrix-operations-tool.git

# Step 2: Navigate to the project folder
cd matrix-operations-tool

# Step 3: Install NumPy
pip install numpy

# Step 4: Run the script
python matrix_operations.py
```

---

## 📁 Project Structure

```
matrix-operations-tool/
│
├── matrix_operations.ipynb    # Google Colab Notebook (main file)
├── matrix_operations.py       # Pure Python script version
└── README.md                  # Project documentation (this file)
```

---

## 🧠 Concepts Used

| Concept | Description |
|---|---|
| `numpy` library | Used for all matrix math operations |
| `np.array()` | Converts user input into a matrix |
| `np.dot()` | Matrix multiplication |
| `np.linalg.det()` | Determinant calculation |
| `.T` property | Matrix transpose |
| `.shape` | Checking matrix dimensions |
| `while` loop | Keeps the menu running until user exits |
| `try/except` | (Optional) Error handling for bad inputs |

---

## ⚠️ Operation Rules

| Operation | Rule |
|---|---|
| Addition / Subtraction | Both matrices must have **same shape** (e.g., 2×2 and 2×2) |
| Multiplication | Columns of A must equal Rows of B (e.g., 2×3 and 3×2) |
| Transpose | Works on **any** matrix |
| Determinant | Matrix must be **square** (e.g., 2×2, 3×3) |

---

## 🛠️ Built With

- [Python 3](https://www.python.org/) — Programming Language
- [NumPy](https://numpy.org/) — Numerical Computing Library
- [Google Colab](https://colab.research.google.com/) — Cloud-based Jupyter Notebook

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@Tanwi20024](https://github.com/Tanwi20024)
- LinkedIn: [tanwi-srivastava-55422a275](www.linkedin.com/in/tanwi-srivastava-55422a275)

---

## 📚 Learning Journey

This is **Project 3** in my Python learning series:

| # | Project | Status |
|---|---|---|
| 1 | Student Data Analysis | ✅ Done |
| 2 | House Price Prediction | ✅ Done |
| 3 | Matrix Operations Tool | ✅ Done |

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and share.

---

> ⭐ If you found this helpful, please **star this repository** — it motivates me to keep building!
