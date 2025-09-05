# 👩‍💼 Human Resources Data Analysis & Insights

## 📌 About the Project

In today’s competitive world, **people are the most valuable asset** of any organization. This project dives deep into HR data to uncover patterns in **employee demographics, salaries, retention, and departmental structure**.

The notebook takes the raw HR dataset and transforms it into actionable insights using **exploratory data analysis (EDA), business-driven questions, and unsupervised learning (PCA & clustering)**.

The goal? To **help HR managers and executives make data-backed decisions** about workforce planning, employee engagement, and retention strategies.

## 🗂️ Dataset Overview

The dataset `HRDataset_v14.csv` contains real-world HR-related fields such as:

* **Employee Demographics** – Age, Gender, Date of Birth.
* **Employment Details** – Department, Job Title, Employment Status.
* **Compensation** – Salary, PayGrades.
* **Performance & Tenure** – Length of Service, Manager, Performance Score.

This makes it suitable for both **descriptive reporting** and **predictive analytics**.

## 🔎 What I Did

1. **Exploratory Data Analysis (EDA)**

   * Inspected dataset shape, columns, unique values, and missing data.
   * Summarized employee demographics and salary distributions.
   * Examined workforce size across departments.

2. **Business Insights**

   * Average salary per department.
   * Turnover analysis: active vs. terminated employees.
   * Age distributions to highlight generational workforce composition.

3. **Visualizations**

   * Histograms of salary & age.
   * Department headcount (bar chart).
   * Employment status (pie chart).

4. **Advanced Analytics**

   * Scaled features using `StandardScaler`.
   * Applied **Principal Component Analysis (PCA)** to reduce dimensionality.
   * Implemented **K-Means clustering** to segment employees.
   * Evaluated clusters using **Silhouette Score** for cohesion and separation.

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/loryneJoy/Human_Resource_ML_Project.git
   cd Human_Resources_EDA
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Human_Resources_EDA_Project.ipynb
   ```

## 🛠️ Tools & Libraries

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Scikit-learn** (StandardScaler, PCA, KMeans)
* **Google Colab** for execution

## 📊 Key Findings

* Salaries vary significantly across departments.
* Certain departments face higher turnover than others.
* Workforce is multi-generational, with age clusters visible.
* PCA + KMeans revealed meaningful **employee clusters** for HR strategy.

## 🌱 Future Work

* Predicting **employee attrition** using supervised ML models.
* Building an interactive **HR dashboard** (e.g., in Power BI or Streamlit).
* Integrating with real-time HR systems for ongoing insights.
