# 🏠 Hyderabad Real Estate Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis (EDA) project on Hyderabad residential property listings using Python. The project focuses on data cleaning, feature engineering, statistical analysis, visualization, and business-driven insights to identify the key factors influencing property prices and investment opportunities in the Hyderabad real estate market.

---

# 📌 Overview

Real estate pricing is influenced by multiple factors such as property size, location, furnishing, property type, and transaction type. Raw property data is often inconsistent and requires preprocessing before meaningful insights can be generated.

This project transforms raw scraped data into an analytical dataset, performs comprehensive exploratory data analysis, and answers business questions using statistical methods and data visualization.

---

# 🎯 Business Problem

Analyze Hyderabad residential property listings to answer key business questions such as:

- Which factors influence property prices the most?
- Which locations have the highest average property prices?
- Does property area significantly affect total price?
- Which property type is the most expensive?
- Does furnishing increase property prices?
- Which BHK configuration commands the highest average price?
- Are new properties priced higher than resale properties?
- Which location and property type combinations form the luxury market?
- What characteristics define luxury properties?
- Which locations offer the best investment opportunities?

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Statistical Analysis | Correlation, Skewness, IQR |
| Development Environment | Google Colab |

---

# 📊 Dataset

The dataset was generated from the companion **Real Estate Web Scraping** project.

| Attribute | Details |
|-----------|---------|
| Domain | Real Estate |
| City | Hyderabad |
| Records | 930 |
| Features | 11 |

---

# ⚙️ Project Workflow

```
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Missing Value Treatment
      │
      ▼
Outlier Detection
      │
      ▼
Univariate Analysis
      │
      ▼
Bivariate Analysis
      │
      ▼
Business Question Analysis
      │
      ▼
Business Insights
      │
      ▼
Conclusion
```

---

# 🧹 Data Cleaning

The dataset was cleaned and standardized before analysis.

Performed the following preprocessing tasks:

- Removed irrelevant columns (Project_Name)
- Converted numerical columns to appropriate data types
- Split Floor into Current Floor and Total Floors
- Created Total Price feature
- Removed unnecessary characters
- Handled missing values
- filled missing records
- Standardized categorical values
- Verified data consistency

---

# ⚡ Feature Engineering

Created new analytical features to improve business analysis.

- Current Floor
- Total Floors
- Total Price

These engineered features enabled deeper analysis of pricing trends and building characteristics.

---

# 📈 Outlier Analysis

Outliers were identified using:

- Boxplots
- Interquartile Range (IQR)

Rather than removing all outliers, they were verified against the business context. Most extreme values represented genuine luxury villas and premium properties, so they were retained to preserve the integrity of the Hyderabad real estate market.

---

# 📉 Exploratory Data Analysis

### Univariate Analysis

Numerical Variables

- Summary Statistics
- Histogram
- KDE Plot
- Box Plot
- Skewness Analysis

Categorical Variables

- Frequency Distribution
- Percentage Distribution
- Count Plot

---

### Bivariate Analysis

The following analyses were performed:

- Correlation Matrix
- Heatmap
- Scatter Plot
- hist plot
- GroupBy Analysis
- Box Plot
- Bar Plot

---

# 📋 Business Questions Answered

- Which factors influence property prices the most?
- Which locations have the highest average property prices?
- Does area significantly affect total property price?
- Which property type is the most expensive?
- Does furnishing increase property prices?
- Which BHK configuration offers the highest average price?
- Are new properties priced higher than resale properties?
- Which Location + Property Type combination commands the highest prices?
- What features characterize luxury properties?
- Which locations provide the best investment opportunities?

---

# 📊 Key Findings

- Area and Price per Sq.ft are the strongest drivers of property prices.
- Premium locations command significantly higher average prices.
- Villas represent the highest-priced property segment.
- Most properties belong to the 2–4 BHK category.
- Fully furnished properties generally have higher prices.
- Luxury properties are concentrated in premium locations and have larger built-up areas.

---

# 💼 Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Missing Value Treatment
- Outlier Detection
- Exploratory Data Analysis
- Statistical Analysis
- Correlation Analysis
- Business Analytics
- Data Visualization
- Business Insight Generation
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


# 🔮 Future Improvements

- Build machine learning models for price prediction
- Develop an interactive Power BI dashboard
- Perform time-series trend analysis
- Integrate additional real estate data sources
- Deploy an end-to-end analytics dashboard

---

**Gyaneshwar Babbili**


### Skills

- Python
- SQL
- Power BI
- Excel
- Machine Learning
- Data Analysis

