## 📌 About the Project

The goal is to explore **all possible combinations** that could lead to the maximum product of three integers. This includes:

- The **three largest positive numbers**.
- The **two most negative numbers** multiplied by the largest positive number.

The algorithm avoids sorting for performance and instead uses **manual tracking** of max/min values.

---

## ⚙️ System Workflow

### 🔁 Iterative Flow
1. Loop through the list once.
2. Track the top 3 max numbers (`max1`, `max2`, `max3`).
3. Track the bottom 2 min numbers (`min1`, `min2`).
4. Compare the product of:
   - `max1 * max2 * max3`
   - `min1 * min2 * max1`
5. Return the greater value.

### 🔁 Recursive Flow
- A recursive version applies the same logic but passes updated variables with each call.

---

## 🗃️ Project Files Overview

| File Name                 | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `Code.py`                 | Main iterative version of the algorithm. Efficient and avoids sorting.      |
| `Recursive_Code.py`       | Alternative recursive approach to calculate the result.                     |
| `Main.py`                 | Pseudocode-style breakdown of the logic used in the recursive algorithm.    |
| `Pseudocode.md`           | Logical flow documentation of the solution, useful for reports/presentation.|

---

## 🧪 Sample Input & Output

```python
arr = [-10, -3, 5, 6, -20]
print(max_product_of_three(arr))  
# Output: 1200  → (-10 * -20 * 6)
```

---
## 🧠 Key Features

- 🧮 Handles both negative and positive numbers.
- 🚀 Runs in linear time: `O(n)`
- 📦 No external libraries needed.
- 🔀 Includes both iterative and recursive implementations.

---

## 🛠️ How to Run the Project

1. Install **Python 3.x** on your system.
2. Clone or download the project files.
3. Place all files in a single directory.
4. Run the main version using:

```bash
python Code.py
````

Or test the recursive version:

```bash
python Recursive_Code.py
```

---

## 👨‍💻 Team Members

**Project Leader:** Amr Yasser Badr

**Team Members:**

* Youssef Mahmoud Younes
* Sama Saeed El-Fishawy