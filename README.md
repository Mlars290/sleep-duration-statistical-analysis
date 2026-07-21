# 🛌 Sleep Duration Statistical Analysis

> Statistical analysis examining how **stress level** and **BMI category** influence sleep duration using a **Two-Way ANOVA** in **R**.

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistical%20Analysis-Two--Way%20ANOVA-blue?style=for-the-badge)
![ggplot2](https://img.shields.io/badge/Visualization-ggplot2-success?style=for-the-badge)

---

## 📖 Overview

This project explores how **stress level** and **BMI category** affect sleep duration using statistical modeling techniques.

Working as a team, we cleaned and prepared the data, engineered categorical variables, performed a **Two-Way ANOVA**, and interpreted both the main effects and interaction effects to better understand factors associated with sleep duration.

This project was completed for **STAT 301 – Analysis of Variance and Multivariate Analysis** at **Metropolitan State University**.

---

## 🎯 Research Question

**How do stress level and BMI category individually—and together—influence sleep duration?**

---

## 📊 Dataset

- **Dataset:** Sleep Health and Lifestyle Dataset
- **Observations:** 364
- **Dependent Variable:** Sleep Duration (hours)
- **Independent Variables:**
  - Stress Level Category
  - BMI Category

---

## 🔬 Methodology

The analysis included:

- Data cleaning and preprocessing
- Feature engineering
- Categorization of stress levels
- Two-Way ANOVA using a linear model (`lm`)
- Type II ANOVA for unbalanced data
- Welch Two-Sample t-tests
- Data visualization using **ggplot2**

---

# 📈 Results

## Interaction Plot

<p align="center">
  <img src="interaction-plot.png" width="700">
</p>

The interaction plot shows that sleep duration decreases as stress levels increase for both BMI groups. The non-parallel lines indicate a significant interaction effect, suggesting that the relationship between stress level and sleep duration differs depending on BMI category.

---

## Mean Sleep Duration by Stress Level and BMI

<p align="center">
  <img src="bar-chart.jpeg" width="700">
</p>

Sleep duration decreases as stress levels increase for both BMI groups. Individuals with a Normal BMI generally slept longer at low and medium stress levels, while at high stress levels the relationship slightly reversed, supporting the significant interaction identified by the ANOVA.

---

# 💡 Key Findings

- Stress level had a statistically significant effect on sleep duration (**p < 0.001**).
- BMI category had a statistically significant effect on sleep duration (**p < 0.001**).
- A significant interaction effect was observed between stress level and BMI category (**p < 0.001**).
- Sleep duration consistently decreased as reported stress levels increased.
- The interaction revealed that the effect of BMI on sleep duration changes under high stress conditions.

---

# 🛠 Skills Demonstrated

- R Programming
- Statistical Analysis
- Two-Way ANOVA
- Hypothesis Testing
- Type II ANOVA
- Welch Two-Sample t-tests
- Data Cleaning
- Feature Engineering
- Data Visualization
- Statistical Interpretation
- Research Reporting

---

# 📁 Repository Structure

```text
sleep-duration-statistical-analysis
│
├── data/
│
├── Sleep_Analysis_TwoWay_ANOVA_Report.docx
├── sleep-anova-analysis.Rmd
├── interaction-plot.png
├── bar-chart.jpeg
└── README.md
```

---

# 👥 Authors

- Maria Larson
- Izzy Mika
- Jiaming Zhang

---

## 📚 Course Information

**Course:** STAT 301 – Analysis of Variance and Multivariate Analysis

**Institution:** Metropolitan State University

**Project Type:** Team Statistical Analysis Project
