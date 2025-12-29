# 📊 Salary Analysis & Exploratory Data Analysis (EDA) Internship Project

## 📌 Project Title
Employee Salary Data Analysis using Python

---

## 📝 Project Description
This project is completed as part of my **internship**.  
The main objective of this project is to perform **Exploratory Data Analysis (EDA)** on employee salary data and visualize insights using Python.

To avoid file-related issues such as `FileNotFoundError`, the dataset is **created directly inside the Python code** instead of loading from an external CSV file.  
This makes the project easy to run in **VS Code** and **Jupyter Notebook**.

---

## 🎯 Objectives
- Understand the structure of employee data  
- Perform Exploratory Data Analysis (EDA)  
- Analyze salary distribution and patterns  
- Visualize relationships between variables  
- Identify missing values, duplicates, and outliers  

---

## 🗂 Dataset Description
- Dataset is **manually created inside the Python code**
- No external CSV file required
- Columns included:
  - **Age** – Employee age
  - **Salary** – Employee salary
  - **Department** – IT, HR, Finance

This approach ensures smooth execution without errors.

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas** – Data analysis and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **VS Code / Jupyter Notebook**

---

## 🔍 Steps Performed in EDA

### 1️⃣ Import Libraries
All required Python libraries were imported.

### 2️⃣ Dataset Creation
Employee data was created directly using a Python dictionary and converted into a Pandas DataFrame.

### 3️⃣ Data Understanding
- Dataset shape
- Column names
- Data types using `info()`

### 4️⃣ Summary Statistics
Calculated:
- Mean
- Minimum
- Maximum
- Standard Deviation

### 5️⃣ Missing Value Check
Verified that the dataset has **no missing values**.

### 6️⃣ Data Visualization
- **Histogram** – Salary distribution  
- **Scatter Plot** – Age vs Salary  
- **Pie Chart** – Department-wise employee distribution  
- **Box Plot** – Outlier detection in salary  

### 7️⃣ Data Quality Checks
- Duplicate record check  
- Outlier identification  

---

## 📈 Sample Visualization Code
```python
plt.hist(df['Salary'])
plt.xlabel('Salary')
plt.ylabel('Frequency')
plt.title('Salary Histogram')
plt.show()
