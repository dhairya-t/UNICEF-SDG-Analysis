# UNICEF SDG Analysis

## Authors

- Dhairya Thakkar
- Avanti Tandon
- Leslie Liu
- Nasywa Talitha

---

## Project Overview

This project aims to analyze the **quality of life of children** across **Africa** and **Asia**, focusing on key **SDG (Sustainable Development Goals)** indicators such as **child mortality rates**, **education levels**, and **access to basic drinking water services**. Our analysis uses data wrangling, hypothesis testing, and visualization to explore differences between the two regions and draw conclusions on how the SDG indicators vary across these continents.

### Guiding Research Question:

**How is the quality of life of children in countries in Africa compared to countries in Asia?**

---

## Table of Contents

1. [Data Sources](#data-sources)
2. [Research Questions](#research-questions)
   - [Child Mortality Rates](#child-mortality-rates)
   - [Educational Profiles](#educational-profiles)
   - [Access to Basic Drinking Water](#access-to-basic-drinking-water)
3. [Data Cleaning and Wrangling](#data-cleaning-and-wrangling)
4. [Statistical Methods](#statistical-methods)
   - [Hypothesis Testing](#hypothesis-testing)
   - [Bootstrapping](#bootstrapping)
   - [K-Means Clustering](#k-means-clustering)
5. [Visualizations](#visualizations)
6. [Key Findings](#key-findings)
7. [Conclusion](#conclusion)

---

## Data Sources

- **Country Indicators Dataset**: Contains various indicators such as child mortality rates, literacy rates, and completion rates.
- **Country Codes Dataset**: Provides region and country codes to differentiate data by continent.
- **SDG Dataset**: Contains Sustainable Development Goals (SDG) scores and trends for various countries, particularly focusing on SDG Goal 3 (Health), Goal 4 (Education), and Goal 6 (Water and Sanitation).

---

## Research Questions

### 1. Child Mortality Rates

**Research Question**: Is the child mortality rate in countries in Africa higher than in countries in Asia?

- Data was cleaned and filtered to compare the under-5 mortality rates and mortality rates among children aged 5-14 years.
- Applied visualizations (histograms and boxplots) and statistical tests (permutation test and bootstrapping) to assess differences in mortality rates between Africa and Asia.

### 2. Educational Profiles

**Research Question**: How do the educational profiles of countries in Africa and Asia differ based on key indicators?

- Focused on secondary school completion rates and youth literacy rates.
- Used clustering and visualizations to compare education quality between the two regions.

### 3. Access to Basic Drinking Water

**Research Question**: How is the proportion of children in countries in Africa using "at least basic drinking water services" compared to countries in Asia?

- Compared the percentage of children with access to basic drinking water and the SDG Goal 6 scores between Africa and Asia.

---

## Data Cleaning and Wrangling

We performed the following key steps for data cleaning and wrangling:

- **Merged** multiple datasets using country codes to match indicators with regions.
- **Filtered** out incomplete and missing data to ensure accuracy.
- **Created new variables**, such as average mortality rate, to summarize data.

Each dataset was processed and joined to ensure consistency between indicators from different sources.

---

## Statistical Methods

### Hypothesis Testing

We used permutation tests to assess the statistical significance of the observed differences in child mortality rates, education, and access to drinking water between Africa and Asia.

### Bootstrapping

Bootstrapping was used to create confidence intervals for child mortality rates, providing a clearer understanding of the variability of these rates between the two regions.

### K-Means Clustering

To further explore the data, K-Means clustering was used to group countries based on education indicators. This helped identify patterns and trends within regions and evaluate SDG goals.

---

## Visualizations

Key visualizations include:

- **Histograms** for child mortality rates, literacy rates, and access to drinking water.
- **Boxplots** comparing regions on various indicators.
- **Scatterplots** visualizing relationships between education and literacy indicators.

---

## Key Findings

1. **Child Mortality**:

   - African countries have significantly higher child mortality rates compared to Asian countries.
   - **Hypothesis Test Result**: Statistically significant difference in mortality rates (p-value < 0.05).

2. **Education**:

   - Asian countries generally have higher literacy rates and completion rates for secondary education than African countries.
   - **Clustering Analysis**: Shows distinct clusters indicating that African countries generally perform lower on education indicators.

3. **Access to Water**:
   - A larger proportion of children in Asian countries have access to basic drinking water compared to African countries.
   - **Hypothesis Test Result**: Statistically significant difference in access to drinking water (p-value < 0.05).

---

## Conclusion

Our analysis shows that the **overall quality of life for children in Asia is better than in Africa** based on the selected SDG indicators. The disparity in child mortality rates, education, and access to drinking water highlights the need for targeted interventions to improve the conditions for children in African countries.
