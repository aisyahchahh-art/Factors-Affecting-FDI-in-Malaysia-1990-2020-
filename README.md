# Factors-Affecting-FDI-in-Malaysia-1990-2020-
Analysed the relationship between FDI inflows and key macroeconomic factors in Malaysia from 1990–2020. Examined the effects of unemployment, inflation, and GDP on FDI using statistical and econometric analysis, and interpreted the results to understand how changes in economic conditions relate to FDI inflows.

# The Relationship Between Unemployment Rate, Inflation Rate, GDP and FDI Inflows in Malaysia (1990–2020)

## 📌 Project Overview

This project examines the relationship between selected macroeconomic indicators and **Foreign Direct Investment (FDI) inflows in Malaysia** from **1990 to 2020**.

The study focuses on three independent variables:

* **Unemployment Rate**
* **Inflation Rate**
* **Gross Domestic Product (GDP)**

The dependent variable is **Foreign Direct Investment (FDI) inflows**.

The purpose of this study is to examine how changes in these economic indicators are associated with FDI inflows into Malaysia and to identify patterns that may help explain Malaysia's investment environment.

## 🎯 Research Objectives

1. To examine the individual impact of unemployment rates, inflation rates, and GDP growth on FDI inflows in Malaysia.
2. To investigate whether fluctuations in unemployment rates, inflation rates, and GDP have led to variations in FDI inflows.
3. To provide evidence-based insights and recommendations related to FDI and Malaysia's macroeconomic environment.

## 📊 Dataset

The study uses **secondary data covering 1990–2020**.

The data for FDI, GDP, inflation rate, and unemployment rate were collected from several sources, including:

* World Bank
* Department of Statistics Malaysia (DOSM)
* Datastream
* Trading Economics
* Macrotrends

The thesis states that the study contains **30 observations** covering the research period.

## 🧩 Variables

| Variable          | Type                 | Description                       |
| ----------------- | -------------------- | --------------------------------- |
| FDI               | Dependent Variable   | Foreign Direct Investment inflows |
| GDP               | Independent Variable | Gross Domestic Product per capita |
| Inflation         | Independent Variable | Inflation rate                    |
| Unemployment Rate | Independent Variable | Unemployment rate                 |

The research model is:

```text
FDI = β₀ + β₁(Unemployment Rate) + β₂(Inflation Rate) + β₃(GDP)
```

The thesis defines GDP as **Gross Domestic Product per capita** in the research model.

## 🛠️ Tools & Methods

### Tools

* **Microsoft Excel**
* **IBM SPSS**

### Statistical Methods

* Multiple Regression Analysis
* ANOVA
* Regression Coefficients (β)
* R-Square (R²)
* Adjusted R-Square
* Multicollinearity Test
* Autocorrelation Test
* White Heteroskedasticity Test

These methods were used to analyse the relationship between FDI and the selected macroeconomic variables.

## 📈 Regression Results

The regression analysis produced the following results:

| Variable          | Coefficient (β) | Standard Error |   Beta | t-value | Significance |
| ----------------- | --------------: | -------------: | -----: | ------: | -----------: |
| Constant          |          10.670 |          3.181 |      — |   3.354 |        0.002 |
| GDP               |           0.167 |          0.172 |  0.183 |   0.973 |        0.339 |
| Inflation         |          -0.141 |          0.480 | -0.056 |  -0.294 |        0.771 |
| Unemployment Rate |          -1.402 |          0.781 | -0.324 |  -1.795 |        0.084 |

**R²:** 0.131
**Adjusted R²:** 0.034

The regression table is reported in Chapter 4 of the thesis.

## 🔍 Model Diagnostic Tests

The study also examined several regression assumptions:

### Multicollinearity

A multicollinearity test was performed to examine whether the independent variables were strongly related to each other.

### Autocorrelation

An autocorrelation analysis was conducted because the dataset consists of observations over time.

### Heteroskedasticity

The **White Test** was used to examine whether the variance of the regression error terms was constant.

The reported White Test produced a **Chi-Square value of 0.131** and a **significance value of 0.765**.

## 💡 Key Findings

The regression results reported in the thesis show:

* GDP had a **positive coefficient** of 0.167.
* Inflation had a **negative coefficient** of -0.141.
* Unemployment Rate had a **negative coefficient** of -1.402.
* The model reported an **R² of 0.131** and an **Adjusted R² of 0.034**.

The thesis also discusses other factors that may influence FDI inflows, including investment policies, economic conditions, exchange rates, and the COVID-19 period.

## 📁 Project Structure

```text
Malaysia-FDI-Analysis/
│
├── README.md
│
├── data/
│   └── malaysia_fdi_1990_2020.xlsx
│
├── analysis/
│   ├── regression_analysis/
│   ├── multicollinearity/
│   ├── autocorrelation/
│   └── heteroskedasticity/
│
├── dashboard/
│   └── FDI_analysis_dashboard.pbix
│
├── report/
│   └── thesis.pdf
│
└── images/
    └── regression_results.png
```

*The folder structure can be adjusted depending on which files you decide to upload to GitHub.*

## 🎓 Academic Project

**Degree:** Bachelor of Science (Hons.) Economics
**University:** Universiti Utara Malaysia (UUM)
**Year:** 2024
**Research Area:** Economics / Macroeconomics / Foreign Direct Investment

## 👩‍💻 Author

**Siti Nur Aisyah Zaharah Binti Abdul Malik**

Bachelor of Science (Hons.) Economics
Universiti Utara Malaysia

## 📚 Research Scope

This project focuses specifically on Malaysia and covers the period **1990–2020**. The analysis is based on secondary economic data and should therefore be interpreted within the scope of the variables, data sources, methodology, and period used in the study.

