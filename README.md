<<<<<<< HEAD
# Employee_Attrition_Analysis
=======
# Employee Attrition Analysis

## 📌 Subtitle:
An exploratory data analysis on factors influencing employee attrition

## 👤 Author:
<b><a href="https://github.com/runTimeeRrorOccuRred" target="_blank">Ayon Das</a></b>

## 📅 Date:
1st July 2025

## 🛠️ Tools Used:
- <a href="https://www.python.org/" target="_blank">Python</a>  
- <a href="https://jupyter.org/" target="_blank">Jupyter Notebook</a>  
- <a href="https://pandas.pydata.org/" target="_blank">Pandas</a>  
- <a href="https://matplotlib.org/" target="_blank">Matplotlib</a>  
- <a href="https://seaborn.pydata.org/" target="_blank">Seaborn</a>  

---

## 📖 Introduction

Employee attrition is a critical concern for organizations as it leads to increased recruitment costs, the loss of organizational knowledge, and declining morale among remaining employees. This project aims to understand the key drivers behind employee attrition by performing an in-depth <b>Exploratory Data Analysis (EDA)</b> using Python.

---

## 🧹 Data Cleaning & Preprocessing

Before analysis, the dataset was cleaned and preprocessed with the following steps:

- ✅ Checked for <b>null values</b> and confirmed no missing data needed imputation.
- ✅ Checked for <b>duplicate rows</b> and removed any duplicates to ensure data quality.
- ✅ <b>Converted numeric columns to categorical types</b> (e.g., Job Level, Education, Performance Rating) where appropriate — especially where the number of unique values was limited.
- ✅ Ensured consistent column naming and formatting for ease of analysis and visualization.

These steps helped optimize memory usage, improve performance, and prepare the data for effective exploratory analysis.

---

## 🎯 Objectives

### Objective 1:
<b>Analyze attrition based on Education Field</b>  
- Identify if specific fields (e.g., Life Sciences, Medical) are more prone to attrition.
- Evaluate performance ratings, promotion history, and job levels for these fields.

### Objective 2:
<b>Understand attrition patterns based on company tenure and prior job experience</b>  
- Focus on employees with only one year at the company.
- Explore how many companies they have worked at previously.

### Objective 3:
<b>Evaluate the effect of commute distance and overtime on attrition</b>  
- Determine if proximity to the office correlates with attrition.
- Study the role of overtime in increasing attrition rates.

### Objective 4:
<b>Examine the relationship between job roles, salary, and attrition</b>  
- Identify which job roles are more vulnerable to attrition.
- Correlate monthly income with attrition likelihood.

---

## 📊 Analysis Highlights

- <b>Education Field:</b>  
  Employees from <b>Life Sciences</b> and <b>Medical</b> backgrounds showed higher attrition, especially those:
  - At <b>job levels 1 and 2</b>
  - With <b>no recent promotions</b>
  - Having <b>performance ratings around 3</b>

- <b>Tenure and Prior Experience:</b>  
  Employees with only <b>one year at the company</b> and <b>limited prior experience</b> (just one previous job) are more likely to leave early.

- <b>Commute and Overtime:</b>  
  Employees who live <b>close to the office (1–2 km)</b> and also work <b>overtime</b> have an attrition rate of <b>28.5%</b>, compared to the overall <b>12.5%</b>.  
  ➤ Proximity doesn’t compensate for work-life imbalance.

- <b>Job Role and Income:</b>  
  Highest attrition observed in:
  - Sales Representatives
  - Sales Executives
  - Laboratory Technicians  
  These roles also had <b>lower monthly income</b> compared to other roles.

---

## 💡 Key Insights

- Employees from Life Sciences and Medical fields in <b>low-level roles</b> with <b>no promotions</b> and <b>average performance</b> are highly vulnerable to attrition.
- <b>New hires</b> with <b>limited past job experience</b> are at risk of leaving within the first year.
- <b>Overtime</b> is a strong predictor of attrition, especially when combined with <b>short commute distances</b>.
- <b>Lower salaries</b> in certain job roles directly relate to higher attrition rates.

---

## 📁 Files Included

- <a href="https://github.com/runTimeeRrorOccuRred/Employee_Attrition_Analysis/blob/main/employee_attrition_docs.pdf" download>Employee_Attrition_Analysis_Report.pdf</a> — The full pdf report  
- <a href="https://github.com/runTimeeRrorOccuRred/Employee_Attrition_Analysis/blob/main/employee_attrition_analysis.ipynb" download>Attrition_EDA_Notebook.ipynb</a> — Jupyter Notebook with code and visualizations *(if included)*

---

## 🧩 Future Improvements

- Incorporate machine learning models to <b>predict attrition risk</b>.
- Perform <b>correlation matrix and feature importance analysis</b>.
- Explore <b>survey-based satisfaction scores</b> if available in the dataset.

---

## 📬 Contact

For any questions or feedback, feel free to reach out via  
<a href="https://github.com/runTimeeRrorOccuRred" target="_blank">GitHub</a> or  
<a href="https://www.linkedin.com/in/ayon-das-4b3212147/" target="_blank">LinkedIn</a>

---

>>>>>>> a7449c7 (first commit)
