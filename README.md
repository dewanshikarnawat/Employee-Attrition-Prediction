# 👩‍💼 Employee Attrition Prediction

Predicting which employees are likely to leave a company using Machine Learning and HR analytics — helping organizations proactively address retention risks.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

Employee attrition (staff turnover) is a major concern for organizations, as losing skilled employees is costly and disruptive. This project uses HR analytics data to build a machine learning model that predicts whether an employee is likely to leave the company, based on factors like job satisfaction, income, work-life balance, and tenure.

The goal is to help HR teams identify at-risk employees early and take preventive action.

## 📊 Dataset

The project uses `HR_attrition.csv`, containing employee records with attributes such as:

- **Demographics:** Age, Gender, Marital Status, Education, Education Field
- **Job details:** Department, Job Role, Job Level, Business Travel, Over Time
- **Compensation:** Monthly Income, Daily Rate, Hourly Rate, Percent Salary Hike
- **Satisfaction & engagement:** Job Satisfaction, Environment Satisfaction, Relationship Satisfaction, Work-Life Balance, Job Involvement
- **Tenure & experience:** Total Working Years, Years at Company, Years in Current Role, Years Since Last Promotion, Years With Current Manager, Number of Companies Worked
- **Target variable:** `Attrition` (Yes/No)

## 🗂️ Project Structure
Employee-Attrition-Prediction/
├── charts/             # Visualizations and plots generated during analysis
├── HR_attrition.csv    # HR analytics dataset
├── analysis.ipynb      # Main Jupyter Notebook — EDA, preprocessing & modeling
├── summary.pdf.pdf     # Summary report of findings
├── LICENSE             # MIT License
└── README.md           # Project documentation

## 🔍 Approach

1. **Data Exploration (EDA)** — Analyzing distributions, correlations, and attrition trends across departments, roles, and demographics.
2. **Data Preprocessing** — Handling categorical variables, feature encoding, and scaling.
3. **Model Building** — Training classification models to predict attrition.
4. **Evaluation** — Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.
5. **Insights** — Identifying the key drivers of employee attrition.

## 📈 Key Insights

> _[Add 2–4 bullet points here summarizing your main findings — e.g., which factors most strongly predict attrition, such as OverTime, Job Satisfaction, or Monthly Income.]_

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run Locally

```bash
# Clone the repository
git clone https://github.com/dewanshikarnawat/Employee-Attrition-Prediction.git

# Navigate into the project directory
cd Employee-Attrition-Prediction

# Launch Jupyter Notebook
jupyter notebook analysis.ipynb
```

## 📉 Results

> _[Add your final model's accuracy/precision/recall/F1-score here once confirmed, e.g.: "The final model achieved XX% accuracy in predicting employee attrition."]_

Visualizations from the analysis are available in the [`charts/`](./charts) folder, and a detailed write-up is available in [`summary.pdf.pdf`](./summary.pdf.pdf).

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

## 🙋‍♀️ Author

**Dewanshi Karnawat**
GitHub: [@dewanshikarnawat](https://github.com/dewanshikarnawat)

---

⭐ If you found this project helpful, consider giving it a star!
