# 🧠 Data Analysis and Data Science Using Python 
# Student-Performance-Analysis 

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-green)](https://seaborn.pydata.org/)

---

## 🎯 Objective
The objective of this project is to **analyze student exam performance data** and answer key analytical questions using Python.  
The project demonstrates core **data analysis**, **statistical exploration**, and **visualization techniques** using fundamental Python libraries — `pandas`, `NumPy`, `matplotlib`, and `seaborn`.

---

## 📂 Dataset
**Dataset:** Student Performance Dataset  
**File:** `student-mat.csv`  
**Source:** Provided by Main Flow Services and Technologies Pvt. Ltd.

**Key Columns:**
- `G1`, `G2`, `G3` — Grades from three evaluation periods  
- `studytime` — Weekly study time  
- `sex` — Gender (M/F)  

---

## 🧩 Project Steps

### 1. **Data Loading**
- Loaded dataset using `pandas.read_csv()` with `sep=';'` (semicolon delimiter).
- Displayed the first five rows using `.head()`.

### 2. **Data Exploration**
- Checked for missing values using `.isnull().sum()`.
- Displayed column data types with `.dtypes`.
- Checked dataset dimensions with `.shape`.

### 3. **Data Cleaning**
- Verified and confirmed no missing values.
- Removed duplicates using `.drop_duplicates()`.

### 4. **Data Analysis**
Answered the following questions:
1. **What is the average score in math (G3)?**  
2. **How many students scored above 15 in their final grade (G3)?**  
3. **Is there a correlation between study time and final grade (G3)?**  
4. **Which gender has a higher average final grade (G3)?**

### 5. **Data Visualization**
Created visualizations using **matplotlib** and **seaborn**:
1. 📊 Histogram of final grades (`G3`)  
2. 🔵 Scatter plot between `studytime` and `G3`  
3. 🟣 Bar chart comparing average scores of male and female students  

All plots were saved locally as PNG files:
- `g3_histogram.png`
- `studytime_vs_g3_scatter.png`
- `avg_g3_by_gender_bar.png`

---

## ⚙️ Technologies Used
| Tool | Purpose |
|------|----------|
| **Python** | Core programming language |
| **Pandas** | Data loading, cleaning, and analysis |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Basic data visualization |
| **Seaborn** | Statistical data visualization and styling |

---

## 🧾 Key Findings
- The **average final math score (G3)** was calculated accurately.  
- A certain number of students scored **above 15 in their final grade**.  
- There exists a **positive correlation between study time and G3**, suggesting that consistent study time improves performance.  
- On average, **female students achieved slightly higher grades** than male students.

---

## 🧠 Learning Outcomes
- Gained hands-on experience in **data cleaning**, **exploration**, and **visualization**.  
- Learned to use `pandas` and `NumPy` for basic statistical operations.  
- Developed skills to create meaningful and well-labeled visualizations.  
- Practiced documenting the entire analysis process in Markdown cells for clarity and presentation.

---

## 📋 Restrictions Followed
- Used only **pandas** and **NumPy** for calculations.  
- Used **matplotlib** and **seaborn** for visualization.  
- Avoided advanced tools like Plotly or external statistical packages.  
- Wrote all code in a **single Jupyter Notebook** with clear Markdown explanations.

---

## 🕒 Deadline Compliance
- The project was completed and submitted **within 7 days** as per Main Flow’s guidelines.  
- This reinforced **time management** and **professional discipline** in completing analytical tasks under deadlines.

---

## 🏁 Conclusion
This project demonstrates how fundamental Python libraries can be used to perform effective data analysis and visualization on real-world datasets.  
It serves as a strong foundation for more advanced data science tasks, such as machine learning, predictive modeling, and business analytics.

---

## 👨‍💻 Author
**Suraj Parida**  
📧 Email: [contact.mainflow@gmail.com](mailto:contact.mainflow@gmail.com)  
📍 Main Flow Services and Technologies Pvt. Ltd.  
🌐 [www.mainflow.in](https://www.mainflow.in)

---

