# Project Title: Testing the Validity of the Environmental Kuznets Curve Hypothesis: Panel Data and Instrumental Variable Approach

![GitHub last commit](https://img.shields.io/github/last-commit/[YourGitHubUsername]/[YourRepoName])
![Language count](https://img.shields.io/github/languages/count/[YourGitHubUsername]/[YourRepoName])
![Top language](https://img.shields.io/github/languages/top/[YourGitHubUsername]/[YourRepoName])

## Description
This research, published in an ISO accredited journal, explores the Environmental Kuznets Curve in 30 Asia-Europe Meeting Summit (ASEM) countries. Utilizing panel data from 1990 to 2014, it employs panel regression and instrumental variable estimation to analyze the link between environmental degradation and economic growth. The study confirms the inverse U-shaped curve of the Environmental Kuznets hypothesis and establishes robust results with added control variables. By determining the curve's turning point, it offers valuable insights for policymakers in Asia and Europe, emphasizing the need for collaborative efforts in advancing sustainability.

---

## Table of Contents
- [Literature Review](#literature-review)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Selection](#model-specification-and-economic-interpretation)
---

## Literature Review
In the study of the Environmental Kuznets Curve (EKC), various methodologies have been applied across different countries, revealing diverse results influenced by regional characteristics. Time-series data confirmed EKC in nations like China, Pakistan, and Turkey, while panel data studies across continents showed varying EKC relationships. This paper contributes by providing a realistic EKC turning point and addressing the endogeneity issue in the EKC model, enhancing the understanding of the link between environmental quality and economic growth.

---

## Exploratory Data Analysis (EDA)
*Details of data used.*

This study uses annual panel data from 1990 to 2014 for 30 Asian and European ASEM partner countries, including various income-level nations like Bangladesh, China, and France. It aims to analyze carbon dioxide emissions against GDP per capita, using World Bank Indicators and Global Economy data. Additional variables like population density and foreign investment serve as controls. Detailed EDA can be found in the paper.

---
## Model Specification and Economic Interpretation
*Explanation of model selection process.*

The project employs a standard EKC model to analyze carbon emissions per capita across ASEM countries (1990-2014). The model includes GDP per capita as a key variable and uses panel regression and instrumental variable estimation. A fixed-effects model, chosen based on Hausman test results (p-value: 0.02295), captures the dynamic relationship between environmental degradation and economic growth. The extended model integrates control variables like population density, energy use, political and civil rights, forest area, and foreign direct investment for robustness.

Key statistical tests, including OLS regression, Breush-Pagan, and Breush-Godfrey/Wooldridge tests, are used to ensure accuracy and address heteroscedasticity and autocorrelation. The study also innovatively uses the old-age dependency ratio as an instrumental variable to correct biases, with significant results confirming the EKC hypothesis. The turning point, a critical aspect of the EKC, is estimated to be around $11,000 for the ASEM countries in the study.

---
## How to Run the Project
