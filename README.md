# Derivable Judgement: A Statistical Decision-Making Model

## 📌 Project Overview

This project applies **Inferential Statistics** to health-related data to understand patterns and relationships between lifestyle factors and diseases. It demonstrates how statistical methods can help analyze data and draw meaningful conclusions.

## 🎯 Objectives

* Understand the fundamentals of inferential statistics.
* Formulate null and alternative hypotheses.
* Calculate confidence intervals, critical values, and p-values.
* Analyze categorical variables using the Chi-square test.
* Perform statistical tests using Python.
* Calculate covariance and correlation between numerical variables.
* Interpret statistical results and draw conclusions.

## Files
- `Derivable_Judgement.ipynb` — full analysis notebook
- `derivable_judgement_dataset.csv` — generated dataset
- `Theory_Notes.pdf` — Part A theory notes with definitions
- `README.md` — project documentation
- `images/` — all labelled charts

## Statistical Methods

The following statistical methods were used to analyze the health dataset:

- **One-Proportion Z-Test:** Used to compare the observed diabetes prevalence with a hypothesized prevalence of 25%.
- **Two-Proportion Z-Test:** Used to compare diabetes proportions between smokers and non-smokers.
- **Welch's Independent-Samples t-Test:** Used to compare glucose levels between individuals with and without diabetes.
- **Chi-Square Test of Independence:** Used to examine the association between smoking status and diabetes.
- **One-Way ANOVA:** Used to compare blood pressure across different age groups.
- **Pearson Correlation:** Used to measure the strength and direction of the linear relationship between age and BMI, and between BMI and blood pressure.
- **95% Confidence Interval:** Used to estimate a plausible range for the population diabetes prevalence.
- **Cramér's V:** Used to measure the strength of the association between smoking status and diabetes.

## 📈 Key Results

| Test | Statistic | p-value | Decision |
| --- | --- | --- | --- |
| One-proportion Z-test (prevalence = 0.25) | z = 4.714 | 2.4 × 10⁻⁶ | Reject H₀ |
| Two-proportion Z-test (smoker vs non-smoker) | z = 6.744 | 1.6 × 10⁻¹¹ | Reject H₀ |
| Welch's t-test (glucose by diabetes status) | t ≈ 36.0 | < 1 × 10⁻¹⁰⁰ | Reject H₀ |
| Chi-square test (smoking × diabetes) | χ² = 58.05 | 2.5 × 10⁻¹³ | Reject H₀ |
| One-way ANOVA (blood pressure by age group) | F ≈ 63 | < 1 × 10⁻³⁰ | Reject H₀ |
| Pearson correlation (age vs BMI) | r = 0.02 | 0.62 | Fail to reject H₀ |
| Pearson correlation (BMI vs blood pressure) | r = 0.36 | ≈ 1 × 10⁻²⁰ | Reject H₀ |

## Additional Findings

- **Diabetes Probability Among Smokers:** 0.450 (45.0%)
- **Diabetes Probability Among Non-Smokers:** 0.160 (16.0%)
- **95% Confidence Interval for Diabetes Prevalence:** (0.296, 0.371)
- **Cramér's V:** 0.311, indicating a moderate association between smoking status and diabetes.

## 📂 Dataset Description

The project uses a health records dataset containing 500 records and 15 columns.

**Key features include:**

* Age and age group
* Weight and BMI
* Gender and region
* Smoking status
* Exercise frequency
* Diabetes and hypertension
* Blood pressure
* Cholesterol and glucose levels
* Visit date

## 🛠️ Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* SciPy


## 📚 Concepts Covered

* Inferential Statistics
* Hypothesis Testing
* Null and Alternative Hypotheses
* Confidence Intervals
* Critical Values and P-values
* Type I and Type II Errors
* Z-test and T-test
* Chi-square Test
* ANOVA
* Covariance
* Correlation

## 🎓 Conclusion

This project demonstrates the practical application of inferential statistics using Python. It combines theoretical concepts with statistical testing, helping to develop skills in data analysis, hypothesis formulation, and interpretation of results.

## ⭐ If you find this project useful

Feel free to explore the dashboard and dataset.

**Made with Python 📊**

## 👩‍💻 Author

**Happy Patel**
Aspiring Data Analyst | Excel | SQL | Power BI | Data Analytics

Mathematics & Advanced Statistics Project
