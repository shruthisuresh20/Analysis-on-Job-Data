# Job Data Analysis Dashboard

##  Project Overview

This project focuses on analyzing job market data to uncover insights into role demand, skills trends, location preferences, and salary ranges. The goal is to support job seekers, recruiters, and educators in making informed, data-driven decisions.

---

##  Objectives

- Analyze job listings across industries and cities
- Identify high-demand job titles and technologies
- Understand salary distributions and experience levels
- Visualize trends across company types, skills, and regions

---

## Dataset Description

| Field Name      | Description                             |
|------------------|-----------------------------------------|
| `Job Title`      | Role or designation                     |
| `Company`        | Hiring organization                     |
| `Location`       | City or region                          |
| `Employment Type`| Full-time, Part-time, Contract          |
| `Experience`     | Required experience level               |
| `Salary`         | Estimated or listed salary              |
| `Skills`         | Listed technical or soft skills         |
| `Posting Date`   | Date job was published                  |

> Dataset compiled from online job boards and cleaned for analysis.

---

##  Technologies Used

| Area            | Tools & Libraries                 |
|------------------|-----------------------------------|
| Programming      | Python                            |
| Data Wrangling   | Pandas, NumPy                     |
| Visualization    | Matplotlib, Seaborn, Plotly       |
| NLP              | NLTK (for skill keyword extraction) |
| Notebook         | Jupyter Notebook (.ipynb)         |

---

##  Methodology

1. **Data Cleaning**:
   - Normalized text fields, removed nulls, standardized salary formats
   - Cleaned and tokenized multi-valued skill entries

2. **Exploratory Data Analysis (EDA)**:
   - Job count by location, title, company
   - Top required skills across roles
   - Salary distributions by role and experience level

3. **Text Analysis**:
   - Extracted most in-demand technical keywords
   - Applied frequency distribution to skill mentions

4. **Visualization**:
   - Dynamic bar charts, word clouds, salary histograms, correlation matrices

---

##  Key Insights

- **Top Hiring Cities**: San Francisco, New York, Seattle
- **In-Demand Roles**: Data Analyst, Software Engineer, Product Manager
- **Common Skills**: Python, SQL, Excel, Communication, AWS
- **Salary Trends**: Higher salaries correlate with cloud, AI, and senior roles
- **Remote Work**: Increasing prevalence across technical roles

---



 
