Retail Store Sales Prediction

This repository provides a complete pipeline for retail sales forecasting using weekly sales data from multiple store outlets. It covers robust data preparation, exploratory analysis, feature engineering, modeling, and forecasting designed to support inventory management and strategic decisions.

---

Project Overview

A retail chain faces inventory challenges tied to demand-supply mismatch. The project analyzes four years of sales data to understand economic and seasonal drivers, benchmark stores, and predict weekly sales for the next 12 weeks.

---

Data Preparation & Cleaning

- Converted and parsed date and categorical features
- Created new year, month, and week columns
- Checked for and removed outliers in weekly sales using IQR method
- Removed duplicates and handled missing values
- Performed descriptive statistics and initial data profiling

---

Exploratory Data Analysis (EDA)

- Analyzed correlations between sales and factors like unemployment, CPI, temperature, and fuel prices
- Visualized seasonality and holiday impacts on sales
- Benchmarked top and low-performing stores annually
- Explored distributions and feature skewness to guide transformations

---

Feature Engineering & Modeling

- Addressed multicollinearity using VIF and correlation analysis
- Applied PowerTransformer and log transformations selectively
- Built models using Decision Tree, Random Forest, and XGBoost with hyperparameter tuning in pipelines
- Evaluated with R² score; XGBoost performed best on test data

---

Time Series & Forecasting

- Decomposed sales into trend, seasonal, and residual components
- Generated 12-week forward sales forecasts per store

---

Key Insights

- Sales negatively influenced by unemployment, with variability across stores
- Strong seasonal and holiday sales patterns identified
- Temperature and CPI exhibit measurable effects on sales
- Significant sales gap exists between highest and lowest performing stores

---

Conclusion

This project demonstrates end-to-end data science skills: from cleansing, EDA, feature engineering to advanced modeling and forecasting—providing actionable insights for retail inventory management.

---

*Explore the notebooks or raise issues for questions or collaboration.*
