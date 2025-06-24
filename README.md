
# 🧠 Mental Health Survey - EDA Project

This project involves Exploratory Data Analysis (EDA) on a survey dataset focused on mental health among tech industry professionals. The goal is to understand patterns in treatment-seeking behavior, workplace support, and risk factors such as gender, age, remote work, and more.

---

## 📌 Problem Statement
Mental health issues are prevalent in the fast-paced tech industry, yet many employees lack access, awareness, or willingness to seek support. This analysis aims to uncover the factors that influence mental health treatment, and help organizations create a more inclusive, well-informed, and supportive culture.

---

## 📊 Dataset Summary
- **Rows:** 1259 (before cleaning)
- **Columns:** Multiple (demographic, work-related, and mental health indicators)
- **Key Features:** Age, Gender, Self-employment, Treatment, Remote Work, Work Interference, Family History

---

## 🛠️ Data Cleaning and Manipulations
- Removed outliers in `Age` using IQR method (kept 13.5 to 49.5 age range)
- Normalized `Gender` to three categories: Male, Female, Other
- Filled missing values in:
  - `self_employed` → "No"
  - `work_interfere` → mode ("Sometimes")
  - `state` → "Not specified"
- Converted data types to appropriate formats (e.g., categorical, datetime)
- Removed or corrected inconsistent entries

---

## 📈 Visualizations (UBM Analysis)
A total of **10+ charts** were created including:
- Age and Gender Distribution
- Treatment by Age, Gender, Remote Work
- Family History and Self-Employment impact
- Company Size vs Benefits
- Work Interference vs Treatment by Gender
- Sunburst, Heatmaps, Stacked Bar Charts for relationship analysis

Each chart includes:
- Why it was selected
- Insights found
- How it supports business impact

---

## 💡 Key Insights
- Majority of tech respondents are aged 25–35 and more likely to seek treatment.
- Males are less likely to seek help, even when work is affected.
- Remote employees are often unaware of available mental health help.
- Employees with a family history of mental illness are more aware and responsive.
- Larger companies offer more support; small firms show awareness gaps.

---

## 🏁 Conclusion
The analysis highlights clear gaps in awareness, support, and treatment behavior. Gender, age, and remote work influence how individuals experience and address mental health. Companies should invest in accessible, well-communicated, and inclusive wellness strategies.

---

## 📌 Suggested Actions for Business
- Increase communication about mental health resources
- Offer virtual counseling for remote teams
- Target interventions based on age, gender, and family history
- Address stigma among male employees
- Encourage wellness participation via self-assessment tools

---

## 📂 Tools Used
| Tool/Library       | Purpose                            |
|--------------------|-------------------------------------|
| Python (Pandas)    | Data manipulation, cleaning         |
| Seaborn & Matplotlib | Visualizations (UBM)             |
| Plotly             | Interactive visuals |
| Jupyter Notebook / Colab | Development environment     |

---

## 📁 Files in this Repository
- `survey.csv` - Original dataset
- `cleaned_mental_health_data.csv` - Cleaned dataset
- `Mental_Health_EDA.ipynb` - Jupyter notebook with complete code
- `README.md` - Project overview and summary

---
