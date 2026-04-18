# biostatistics-lifestyle-risk-analysis
Biostatistical analysis of lifestyle risk factors and BMI

##  Project Overview

This project investigates the relationship between demographic and lifestyle factors and Body Mass Index (BMI), a key indicator of chronic disease risk. Using statistical modeling, hypothesis testing, and data visualization, the analysis aims to identify significant predictors of BMI and obesity.

The project follows a structured biostatistical workflow, including data cleaning, exploratory analysis, regression modeling, and inference.

---

##  Objectives

* Analyze the distribution and variability of BMI
* Identify demographic factors associated with BMI
* Perform hypothesis testing to evaluate group differences
* Build regression models to quantify relationships
* Assess predictors of obesity using logistic regression

---

## Dataset

* Source: Harvard Dataverse
* File: `Combined_Data_22236F.csv`
* Variables include:

  * Demographics: Gender, Age, Race, Marital Status, Education, Occupation
  * Anthropometrics: Height, Weight, BMI

---

## Methods

### Data Processing

* Handling missing values
* Encoding categorical variables
* Feature engineering (obesity classification: BMI ≥ 30)

### Statistical Analysis

* **Linear Regression (OLS)** → Modeling BMI
* **Logistic Regression** → Predicting obesity risk
* **Hypothesis Testing (t-test)** → Gender differences in BMI

### Visualization

* Distribution plots (BMI)
* Scatter plots (Age vs BMI)
* Boxplots (BMI by Gender)
* Correlation heatmap

---

## Key Findings

* BMI shows a **moderately right-skewed distribution** with variability across individuals
* A **modest positive association** exists between age and BMI
* **Significant differences in BMI by gender** were observed (p < 0.05)
* Regression analysis indicates that BMI is influenced by multiple factors, though only a subset are statistically significant
* Logistic regression identified **gender and occupation** as relevant predictors of obesity risk
* Strong correlations exist between **BMI, weight, and obesity**, while most demographic variables show weaker associations

---

## Limitations

* Cross-sectional data limits causal inference
* Potential multicollinearity among related variables (e.g., BMI, weight)
* Some models showed convergence limitations
* Important lifestyle variables (e.g., diet, physical activity) are not included

---

## Conclusion

The analysis highlights that BMI and obesity risk are influenced by a combination of demographic and behavioral factors, though much of the variability remains unexplained. These findings emphasize the multifactorial nature of chronic disease risk and the importance of incorporating broader lifestyle and clinical variables in future analyses.

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Seaborn & Matplotlib
* Statsmodels
* SciPy

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to project
cd your-repo-name

# Install dependencies
pip install pandas numpy matplotlib seaborn statsmodels scipy

# Open Jupyter Notebook
jupyter lab
```

---

## Project Structure

```
├── data/
│   └── Combined_Data_22236F.csv
├── notebooks/
│   └── biostatistics_lifestyle-risk_chronic-disease_regression-analysis.ipynb
├── README.md
```

---

## Author

Serve Heidari
Biostatistician | Data Analyst
