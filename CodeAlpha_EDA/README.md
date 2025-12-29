# 📊 Exploratory Data Analysis (EDA) Project

## 📌 Task 2: Exploratory Data Analysis (EDA)

This project demonstrates **Exploratory Data Analysis (EDA)** using Python, where the dataset is **created directly inside the code** instead of loading from an external CSV file.  
This approach avoids file-related errors and allows the code to run directly in **VS Code or Jupyter Notebook**.

---

## 🎯 Objectives

The main objectives of this EDA task are:

- Ask meaningful questions before analyzing data  
- Understand data structure, variables, and data types  
- Identify patterns and trends using statistics and visualization  
- Validate assumptions through analysis  
- Detect potential data issues such as missing values, duplicates, and outliers  

---

## 📂 Dataset Description

- The dataset is **manually created inside the Python code** using a dictionary.
- No external CSV file is required.
- The dataset contains the following columns:
  - **Age** – Employee age
  - **Salary** – Employee salary
  - **Department** – Employee department (IT, HR, Finance)

This method ensures the program runs without `FileNotFoundError`.

---

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical plots  
- **VS Code / Jupyter Notebook**

---

## 🔍 Steps Performed in EDA

### 1. Import Libraries
Required Python libraries were imported.

### 2. Dataset Creation
Employee data was created directly within the Python code using Pandas DataFrame.

### 3. Meaningful Questions
Basic analytical questions were defined before performing EDA.

### 4. Data Structure Exploration
- Dataset shape
- Column names
- Data types using `info()`

### 5. Summary Statistics
Statistical measures such as mean, minimum, maximum, and standard deviation were calculated.

### 6. Missing Value Check
Verified that the dataset contains no missing values.

### 7. Data Visualization
- **Histogram** – Salary distribution  
- **Scatter Plot** – Age vs Salary relationship  
- **Pie Chart** – Department-wise employee distribution  

### 8. Hypothesis Testing
Calculated average salary to validate assumptions.

### 9. Data Issue Detection
- Checked duplicate records  
- Identified outliers using boxplot  

---

## 📈 Key Insights

- Salary distribution was clearly visualized  
- Relationship between age and salary was observed  
- No missing values were present  
- Outliers in salary were identified  

---

## ✅ Conclusion

Exploratory Data Analysis helped in understanding the dataset, identifying trends, and ensuring data quality.  
Creating the dataset directly in code makes the project simple, portable, and error-free for beginners and internship submissions.

---

## 🚀 How to Run the Project

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
