# 📊 Data Analysis & Visualization Program


A simple **Menu-Driven Python Project** developed using **Pandas**, **Matplotlib**, and **Seaborn**. This project allows users to load a CSV dataset, perform data analysis, handle missing values, generate statistics, create different types of graphs, and save visualizations.

clilck here to see video:https://drive.google.com/drive/home
---

# 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 📈 Matplotlib
- 🎨 Seaborn

---

# ✨ Features

- 📂 Load CSV Dataset
- 🔍 Explore Dataset
- 🔄 Sort and Filter Data
- 🧹 Handle Missing Values
- 📊 Generate Descriptive Statistics
- 📈 Create Different Types of Graphs
- 💾 Save Graphs as PNG
- 🛡️ Exception Handling using Try-Except
- 📋 Menu Driven Interface

---

# 📁 Project Structure

```text
Data-Analysis-Visualization/
│
├── data_analysis.py
└── parth.csv
```

> **Note:** Agar tumhari Python file ka naam `main.py` ya kuch aur hai, to `data_analysis.py` ki jagah wahi naam likh dena.

---

# 📥 Required Libraries

Install the required libraries using:

```bash
pip install pandas matplotlib seaborn
```

---

# ▶️ Run the Project

```bash
python data_analysis.py
```

---

# 🖥️ Program Menu

```text
========== Data Analysis & Visualization Program ==========

1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit

===========================================================

Enter your choice:
```

---

# 📂 Dataset Used

**File Name:** `parth.csv`

The dataset should contain columns such as:

```text
Product    Sales    Profit
```

---

# 📌 Sample Outputs

## 📂 Load Dataset

```text
Enter CSV file name:
parth.csv

Dataset Loaded Successfully!

     Product   Sales   Profit
0     Laptop   50000   12000
1     Mobile   30000    7000
2     Tablet   20000    4000
3      Mouse    5000    1200
4   Keyboard    7000    1800
```

---

## 🔍 Explore Data

```text
1. Display First 5 Rows
2. Display Last 5 Rows
3. Display Column Names
4. Display Data Types
5. Display Basic Information
```

### Output

```text
     Product   Sales   Profit
0     Laptop   50000   12000
1     Mobile   30000    7000
2     Tablet   20000    4000
3      Mouse    5000    1200
4   Keyboard    7000    1800
```

---

## 🔄 Sort Data

```text
Enter column name:
Sales
```

### Output

```text
     Product   Sales   Profit
3      Mouse    5000    1200
4   Keyboard    7000    1800
2     Tablet   20000    4000
1     Mobile   30000    7000
0     Laptop   50000   12000
```

---

## 🔎 Filter Data

```text
Enter column name:
Sales

Enter filter value:
10000
```

### Output

```text
     Product   Sales   Profit
0     Laptop   50000   12000
1     Mobile   30000    7000
2     Tablet   20000    4000
```

---

## 🧹 Handle Missing Values

```text
==== Handle Missing Data ====

1. Display Rows with Missing Values
2. Fill Missing Values with Mean
3. Drop Rows with Missing Values
4. Replace Missing Values
```

---

## 📊 Descriptive Statistics

```text
              Sales        Profit
count      5.000000      5.000000
mean   22400.000000   5200.000000
std    18087.564000   4325.000000
min     5000.000000   1200.000000
25%     7000.000000   1800.000000
50%    20000.000000   4000.000000
75%    30000.000000   7000.000000
max    50000.000000  12000.000000
```

---

# 📈 Visualizations Included

📊 Bar Plot

📉 Line Plot

📦 Histogram

🔴 Scatter Plot

🥧 Pie Chart

📚 Stack Plot

---

## 💾 Save Visualization

```text
Enter file name:
graph

Visualization saved as graph.png successfully!
```

---

# 🎯 Learning Outcomes

✅ Reading CSV files using Pandas

✅ Exploring DataFrames

✅ Sorting and Filtering Data

✅ Handling Missing Values

✅ Generating Descriptive Statistics

✅ Creating Different Charts

✅ Saving Graphs

✅ Exception Handling using Try-Except

---

# 🚀 Future Enhancements

- 📄 Excel File Support
- 📊 Correlation Heatmap
- 📦 Box Plot
- 🌐 GUI using Tkinter
- 📈 Multiple Dataset Support
- 🎨 Better User Interface

---

# 👨‍💻 Author

**Simran Gohel**

---

# ⭐ Thank You!

If you like this project, don't forget to ⭐ the repository.
