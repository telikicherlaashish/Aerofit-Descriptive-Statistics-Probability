# Aerofit-Descriptive-Statistics-Probability
Analyzed Aerofit treadmill customer data to identify purchasing patterns and build customer profiles. Performed EDA using Python to study demographic and behavioral factors affecting product choice. Created visualizations, contingency tables, and probability analysis to generate insights for targeted marketing and product recommendations.

# Aerofit Treadmill Customer Analysis

## Project Overview

Aerofit is a leading fitness equipment brand that manufactures treadmills, exercise bikes, and other fitness accessories. The company offers multiple treadmill models designed for customers with different fitness needs and budgets.

This project focuses on **analyzing customer data to understand the characteristics of customers who purchase different Aerofit treadmill products.** The goal is to build **customer profiles for each treadmill type** and identify patterns that can help the business recommend the most suitable product to new customers.

The analysis includes **descriptive analytics, probability analysis, and data visualization** to generate insights that support better marketing and product recommendation strategies.

---

## Business Problem

The market research team at Aerofit wants to understand **how customer characteristics differ across the three treadmill products** offered by the company.

The objectives are:

- Identify the **target audience for each treadmill model**
- Understand how **customer demographics influence product purchase**
- Analyze **customer usage behavior**
- Calculate **marginal and conditional probabilities** of product purchases
- Generate **customer profiles for each treadmill product**

The insights will help Aerofit **recommend the right treadmill to potential customers and improve marketing strategies.**

---

## Product Portfolio

Aerofit currently offers three treadmill models:

| Product | Description | Price |
|------|-------------|------|
| KP281 | Entry-level treadmill | $1500 |
| KP481 | Mid-level treadmill for regular runners | $1750 |
| KP781 | Advanced treadmill with premium features | $2500 |

---

## Dataset Description

The dataset contains information about customers who purchased treadmills from Aerofit stores in the past three months.

| Column | Description |
|------|-------------|
| Product | Treadmill model purchased (KP281, KP481, KP781) |
| Age | Customer age in years |
| Gender | Male or Female |
| Education | Years of education |
| MaritalStatus | Single or Partnered |
| Usage | Average number of times the treadmill will be used per week |
| Income | Annual income of the customer ($) |
| Fitness | Self-rated fitness level (1 = Poor, 5 = Excellent) |
| Miles | Average number of miles expected to run/walk per week |

---

## Project Objectives

The analysis aims to answer the following questions:

- What percentage of customers purchase each treadmill product?
- Do **age, gender, marital status, or income** influence treadmill purchases?
- What type of customers buy **entry-level vs advanced treadmills**?
- How does **fitness level affect product selection**?
- What is the **probability of a specific customer type purchasing a particular treadmill**?

---

## Data Analysis Steps

### 1. Data Understanding

- Import the dataset
- Check dataset shape
- Inspect data types
- Convert categorical attributes to **category type if required**
- Generate statistical summaries

---

### 2. Non-Graphical Analysis

Non-graphical analysis was performed to understand the basic structure of the dataset.

Steps performed:

- Value counts of product purchases
- Unique values for categorical variables
- Frequency distribution of customer attributes
- Creation of **two-way contingency tables**

Example analysis:

- Percentage of customers purchasing each treadmill
- Distribution of gender across treadmill models
- Income distribution across products

---

### 3. Visual Analysis

Visualization helps identify patterns and relationships between variables.

### Univariate Analysis

Used to understand the distribution of individual variables.

Plots used:

- Histograms
- Distplots
- Countplots

Variables analyzed:

- Age
- Income
- Fitness
- Usage
- Miles
- Product distribution

---

### Bivariate Analysis

Used to analyze relationships between two variables.

Plots used:

- Boxplots
- Countplots
- Histplots

Relationships analyzed include:

- Product vs Age
- Product vs Income
- Product vs Fitness
- Product vs Usage
- Product vs Gender
- Product vs Marital Status

---

### Correlation Analysis

Correlation analysis was performed to understand relationships among numerical variables.

Techniques used:

- Heatmaps
- Pairplots

Variables analyzed:

- Age
- Income
- Fitness
- Usage
- Miles

---

## Probability Analysis

Probability analysis helps understand **customer behavior and purchase likelihood.**

### Marginal Probability

Marginal probability represents the **overall probability of purchasing each treadmill product.**

Example:

| Product | Probability |
|------|-------------|
| KP281 | P(KP281) |
| KP481 | P(KP481) |
| KP781 | P(KP781) |

---

### Conditional Probability

Conditional probability helps answer questions such as:

- What is the probability that **a male customer buys KP781?**
- What is the probability that **a high-income customer purchases KP781?**
- What is the probability that **a beginner fitness customer buys KP281?**

These probabilities are calculated using **contingency tables with pandas.crosstab().**

---

## Missing Value and Outlier Detection

The dataset was checked for:

### Missing Values
- Verified whether any columns contain null values.

### Outlier Detection

Outliers were identified using:

- Boxplots
- Comparison of **mean vs median values**
- Descriptive statistics

Variables checked:

- Age
- Income
- Miles
- Usage

---

## Key Insights

Some key insights derived from the analysis include:

- The **KP281 treadmill is the most purchased product**, indicating high demand for entry-level equipment.
- Customers with **higher income levels are more likely to purchase KP781**, the premium treadmill.
- Customers with **higher fitness levels and higher usage frequency prefer advanced treadmills.**
- Younger customers tend to purchase **entry-level treadmills**, while experienced runners prefer higher-end models.
- Customers who expect to run more miles per week are more likely to choose **KP781**.

---

## Customer Profiling

Based on the analysis, the following customer profiles were identified:

### KP281 – Entry-Level Customers
- Beginner fitness levels
- Lower to mid income
- Lower usage frequency
- Casual walkers or runners

### KP481 – Mid-Level Customers
- Moderate fitness level
- Regular treadmill usage
- Medium income group
- Fitness enthusiasts

### KP781 – Advanced Customers
- High income group
- High fitness level
- Frequent treadmill usage
- Serious runners or athletes

---

## Business Recommendations

Based on the insights, the following recommendations can help Aerofit improve its sales strategy:

1. Promote **KP281 to beginner fitness customers** and people starting their fitness journey.

2. Target **KP481 toward regular gym users and fitness enthusiasts** who want better features but moderate pricing.

3. Focus **KP781 marketing on high-income and serious fitness users** who require advanced treadmill features.

4. Use **customer fitness level and expected usage as key factors in product recommendation.**

5. Implement **personalized product suggestions in stores and online platforms** based on customer profile data.

---

## Tools and Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab

---


---

## Conclusion

This project demonstrates how **descriptive analytics, probability analysis, and visualization techniques** can be used to understand customer behavior.

The insights from this analysis help Aerofit:

- Identify **target customers for each treadmill**
- Improve **product recommendations**
- Develop **more effective marketing strategies**

These insights enable **data-driven decision making** to support Aerofit's business growth.
