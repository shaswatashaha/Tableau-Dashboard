
# 📊 HR Analytics Dashboard

## 🔗 Live Dashboard

👉 *https://public.tableau.com/views/HR_DashBoard_17747188525230/HRSummary?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link*



---

## 🚀 Overview

This project is an **end-to-end HR Analytics Dashboard** designed to simulate real-world workforce analysis. It combines **synthetic data generation using Python** with **interactive visualization in Tableau** to provide actionable HR insights. This project demonstrates the ability to build a **complete data workflow**, from data generation to visualization, while focusing on solving real-world business problems in HR analytics.

The dashboard supports both:

* **High-level summaries** for strategic decision-making
* **Detailed employee-level analysis** for deeper insights

![Overview](images/HR_Summary.png)
![Overview](images/HR_Details.png)

---

## 🎯 Objective

To help HR managers:

* Track hiring and attrition trends
* Analyze workforce demographics
* Identify salary patterns and disparities
* Explore employee-level data dynamically

---

## 🧩 Dashboard Structure

### 📌 1. Summary View

#### 🔹 Overview

* Total number of:

  * Hired employees
  * Active employees
  * Terminated employees
* Hiring vs termination trends over time
* Employee distribution by:

  * Department
  * Job Title
* HQ vs Branch comparison (New York as HQ)
* Geographic distribution (State & City)

---

#### 🔹 Demographics

* Gender ratio analysis
* Distribution across:

  * Age groups
  * Education levels
* Employee count by:

  * Age group
  * Education level
* Correlation:

  * Education vs Performance rating

---

#### 🔹 Income Analysis

* Salary comparison:

  * Across education levels
  * Between genders
* Relationship between:

  * Age and salary
  * Department-wise salary trends

---

### 📋 2. Employee Records View

* Detailed employee table including:

  * Name
  * Department
  * Job Title
  * Gender
  * Age
  * Education
  * Salary
* Dynamic filtering across all columns

---

## 🧪 Data Generation

A custom Python script was developed to generate a **realistic HR dataset of 8,950 records** with controlled distributions and constraints.

### 🔧 Dataset Features

* Unique Employee ID
* Randomly generated names
* Gender distribution:

  * 46% Female
  * 54% Male
* Location mapping (State & City)
* Hire dates (2015–2024 with weighted probabilities)
* Department and job title hierarchy
* Education level mapped to job roles
* Performance ratings with defined probabilities
* Overtime status (30% Yes, 70% No)
* Salary ranges based on role and department
* Birth dates consistent with job roles and hiring dates
* 11.2% employee attrition with valid termination dates
* Adjusted salary based on:

  * Gender
  * Education
  * Age

---

## 🛠️ Tech Stack

* **Python (Pandas, NumPy)** – Data generation & preprocessing
* **Tableau** – Data visualization & dashboard creation
* **GitHub** – Version control & project showcase

---

## 📊 Key Insights
* **Workforce Composition, Terminations & Geography:** Analysed **8,950** employee records, comprising **7,984** active employees and **966** terminated employees (**10.8%** recorded termination proportion). Across seven departments, **Operations (30.4%)**, **Sales (20.5%)**, and **Customer Service (18.7%)** account for approximately **69.5%** of the active workforce. **Finance** has the highest departmental termination proportion (**13.9%**), compared with **9.7%** in **Marketing**. Approximately **70%** of active employees are based in **New York (HQ)**, while **30%** work across regional branches.
* **Education, Performance & Compensation:** Across all 8,950 records, average salary increases from approximately **$62.1K** among High School graduates to **$86.0K** among PhD holders (**38.4%** difference). The proportion of employees rated *Excellent* also varies by education level, ranging from **12.9%** among High School graduates to **35.4%** among Master's and **47.7%** among PhD holders.
* **Gender Representation & Compensation Analysis:** Active employees are **53.7% Male** and **46.3% Female**. Across all records, male Bachelor's holders earn approximately **12.0%** more on average than female counterparts, while female employees have higher average salaries among Master's (approximately **$86.3K vs. $79.5K**) and PhD holders (**$92.7K vs. $79.7K**). Average salaries across job titles range from approximately **$60.6K** for HR Assistants to **$125.1K** for Finance Managers. *(Note: These are descriptive, unadjusted comparisons rather than causal or pay-equity conclusions.)*

---

## 💼 Business Impact

This dashboard enables:

* Data-driven HR decision-making
* Identification of compensation gaps
* Improved workforce planning
* Better understanding of employee demographics

---

## 🧠 Skills Demonstrated

* Data Generation & Simulation
* Exploratory Data Analysis (EDA)
* Data Visualization & Storytelling
* Dashboard Design (Tableau)
* Business Insight Development

---

## 📂 Project Structure

```
HR-Analytics-Dashboard/
│
├── images/
│   ├── HR_Summary.png
│   ├── HR_Details.png
│
└── README.md
```

---

## 🙏 Acknowledgement

This project was completed by following an online tutorial by Data with BaRAA as part of my hands-on learning in data analytics and Tableau dashboard development.

👉 *https://www.datawithbaraa.com/wiki/tableau#tableau-hr-project*

