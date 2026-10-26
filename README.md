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
- **One-Way ANOVA:** Used to compare blood pressure across five age groups.
- **Pearson Correlation:** Used to measure the strength and direction of linear relationships between numerical variables.
- **Spearman Correlation:** Used to measure the strength of monotonic relationships between numerical variables.
- **95% Confidence Interval:** Used to estimate the population mean age.
- **Covariance:** Used to examine how two numerical variables vary together.

## Key Results

| Test | Statistic | p-value | Decision |
| --- | --- | --- | --- |
| One-Proportion Z-Test (diabetes prevalence = 0.25) | z = -10.535 | Approximately 0 | Reject H₀ |
| Two-Proportion Z-Test (smoker vs non-smoker) | z = 1.090 | 0.27586 | Fail to Reject H₀ |
| Welch's t-Test (glucose by diabetes status) | t = 3.911 | 0.0007 | Reject H₀ |
| Chi-Square Test (smoking status × diabetes) | χ² = 1.184 | 0.5533 | Fail to Reject H₀ |
| One-Way ANOVA (blood pressure by age group) | F = 45.730 | 1.0693 × 10⁻³² | Reject H₀ |
| Pearson Correlation (age vs BMI) | r = -0.019 | 0.6749 | Fail to Reject H₀ |
| Pearson Correlation (BMI vs blood pressure) | r = 0.458 | 2.604 × 10⁻²⁷ | Reject H₀ |
| Pearson Correlation (age vs blood pressure) | r = 0.551 | 5.069 × 10⁻⁴¹ | Reject H₀ |
| Pearson Correlation (cholesterol vs blood pressure) | r = 0.442 | 2.403 × 10⁻²⁵ | Reject H₀ |


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
