# VEDA AI & ML Internship – Task 21
## Missing Value Analysis

### 📌 Project Overview
This project focuses on identifying and analyzing missing values in a dataset using Python and its data analysis libraries. Missing Value Analysis is an important data preprocessing step that helps improve data quality and prepares datasets for further analysis and machine learning applications.

### 🎯 Objective
- Identify missing values in a dataset.
- Calculate missing-value counts for each column.
- Calculate the percentage of missing values.
- Generate a summary table of missing values.
- Identify columns that require missing-value treatment.
- Visualize missing values using a bar chart.

### 🛠️ Technologies Used
- **Programming Language:** Python
- **Data Analysis:** Pandas
- **Numerical Computing:** NumPy
- **Data Visualization:** Matplotlib
- **Development Environment:** Jupyter Notebook
- **Dataset Format:** CSV

### 📂 Project Structure
```text
VEDA-Task-21-Missing-Value-Analysis/
│
├── Missing_Value_Analysis.ipynb
├── dataset.csv
└── README.md
```

### 📊 Dataset Description
A sample employee dataset was created to demonstrate missing-value analysis.

The dataset contains **10 records and 4 columns**.

| Column | Description |
|---|---|
| Name | Employee name |
| Age | Employee age |
| Salary | Employee salary |
| Department | Employee department |

Some values in the Age, Salary, and Department columns are intentionally missing to demonstrate the analysis process.

### ⚙️ Tasks Performed

**1. Import Libraries**

Imported Pandas, NumPy, and Matplotlib for data manipulation, numerical operations, and visualization.

**2. Create and Load the Dataset**

Created a sample employee dataset using Pandas and NumPy, saved it as a CSV file, and loaded it for analysis.

**3. Inspect Dataset Information**

Checked the dataset dimensions, column names, data types, and non-null values.

**4. Identify Missing Values**

Used Pandas `isnull()` and `sum()` methods to calculate the number of missing values in each column.

**5. Calculate Total Missing Values**

Calculated the total number of missing values across the dataset.

**6. Calculate Missing-Value Percentages**

Calculated the percentage of missing values in each column using the total number of records.

**7. Generate a Summary Table**

Combined missing-value counts and percentages into a single summary table.

**8. Identify Columns Requiring Treatment**

Identified columns containing missing values for further investigation and preprocessing.

**9. Visualize Missing Values**

Created a bar chart using Matplotlib to compare missing-value counts across columns.

### 📈 Results

The analysis produced the following results:

| Column | Missing Values | Missing Percentage |
|---|---:|---:|
| Name | 0 | 0% |
| Age | 3 | 30% |
| Salary | 3 | 30% |
| Department | 2 | 20% |
| **Total** | **8** | — |

**Dataset Summary**
- Total records: 10
- Total columns: 4
- Total missing values: 8
- Columns containing missing values: Age, Salary, and Department
- Column without missing values: Name

### 🔍 Key Observations
- The Age column contains 3 missing values, representing 30% of its records.
- The Salary column contains 3 missing values, representing 30% of its records.
- The Department column contains 2 missing values, representing 20% of its records.
- The Name column contains no missing values.
- Age, Salary, and Department require further investigation before using the dataset for subsequent analysis.

### 🧹 Missing-Value Treatment
This task focuses on detecting and analyzing missing values rather than modifying the original dataset.

Possible treatment methods include:
- **Mean imputation:** Filling missing numerical values with the mean.
- **Median imputation:** Filling missing numerical values with the median.
- **Mode imputation:** Filling missing categorical values with the most frequent value.
- **Row or column removal:** Removing incomplete records or columns when justified.

The appropriate method depends on the dataset, the reason for missingness, and the intended application.

### ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Open a terminal in the project folder.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Missing_Value_Analysis.ipynb`.
6. Run all cells from top to bottom.
7. Review the missing-value summary table and bar chart.

### 💡 Learning Outcomes
- Learned to detect missing values using Pandas.
- Practiced column-wise missing-value counting.
- Calculated missing-value percentages.
- Created summary tables for data quality analysis.
- Identified columns requiring preprocessing.
- Visualized missing data using Matplotlib.
- Understood the importance of data cleaning before machine learning.

### 📝 Conclusion
Missing Value Analysis was successfully performed using Python, Pandas, NumPy, and Matplotlib. The analysis identified 8 missing values in the sample dataset, calculated column-wise missing-value percentages, generated a summary table, and visualized the results using a bar chart.

This task demonstrates a fundamental data preprocessing technique that helps identify incomplete data and supports informed decisions before further data analysis or machine learning model development.

### 👨‍💻 Author
**Divakar R**

B.E. Electronics and Communication Engineering

### 🎓 Internship
VEDA AI & ML Internship – Task 21

---

⭐ If you find this project useful, feel free to explore the repository and learn more about data preprocessing with Python.
