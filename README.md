# Black Friday Sales - Exploratory Data Analysis (EDA)

## Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset derived from an e-commerce platform's Black Friday sales. The objective is to investigate consumer purchasing patterns, demographic influences, and product-level trends to derive actionable insights. Through this analysis, we aim to understand how different factors impact sales and identify meaningful patterns within the data.

## Goals of the Project

The primary goals of this project are:

1. **Understand the customer base**:
   - Analyze demographic distributions (age, gender, city type).
   - Identify key consumer segments and their purchasing behavior.

2. **Analyze purchase patterns**:
   - Examine variations in sales by product categories.
   - Discover trends in purchasing amounts across different demographic groups.

3. **Identify insights for business strategy**:
   - Highlight factors influencing higher purchase volumes.
   - Provide visualizations to make complex trends comprehensible.

## Dataset Description

The dataset used for this analysis contains anonymized sales information, with the following key columns:

- **User_ID**: Unique identifier for each customer.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the customer (`M` for Male, `F` for Female).
- **Age**: Age group of the customer (e.g., `0-17`, `18-25`, `26-35`).
- **Occupation**: Numerical representation of the customer's profession.
- **City_Category**: Categorization of the city (`A`: Metro, `B`: Urban, `C`: Rural).
- **Stay_In_Current_City_Years**: How long the customer has stayed in their current city.
- **Purchase**: Purchase amount for a single transaction (numerical value).

### Dataset Insights

- Size: The dataset includes thousands of transactions, making it suitable for statistical and exploratory analysis.
- Source: Simulated dataset representing real-world Black Friday sales scenarios.

## Analysis Workflow

The project workflow involves the following steps:

1. **Data Cleaning and Preparation**:
   - Handling missing values and outliers.
   - Formatting and encoding categorical variables for analysis.

2. **Descriptive Statistics**:
   - Summary statistics for understanding data distributions.
   - Correlation analysis to find relationships between variables.

3. **Visualization**:
   - Creating detailed plots to uncover trends:
     - Bar charts and histograms for demographic analysis.
     - Heatmaps for correlations.
     - Boxplots for purchase behavior across groups.

4. **Key Insights and Reporting**:
   - Documenting key findings with visuals.
   - Suggestions for strategic business actions.

## Visualizations

The project includes various visualizations such as:

- **Demographic Analysis**:
  - Distribution of customers by gender, age, and city category.
- **Purchase Trends**:
  - Average purchase amount segmented by age, occupation, and city type.
- **Product Trends**:
  - Top-selling product categories.
  - Insights into products favored by different demographics.

## Tools and Libraries Used

This project leverages the following Python libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations and efficient data handling.
- **Matplotlib and Seaborn**: For data visualization and graphical representation.
- **Scikit-learn (if needed)**: For preprocessing and feature engineering.
- **Jupyter Notebook**: For interactive data analysis and sharing insights.
Gender Influence:
Males contribute to a higher percentage of sales, but females show higher average purchases in certain age groups.
Age and Purchase Behavior:
Age group 26-35 makes the highest purchases, indicating this as a prime target demographic.
City and Occupation Insights:
City Category B shows the highest number of transactions, while customers with certain occupations show higher average spends.
Business Recommendations:
Develop targeted marketing campaigns for the 26-35 age group.
Focus on expanding offerings in City Category B to capitalize on its purchasing power.
Personalize promotions based on demographic data to increase average spend per user.
https://www.kaggle.com/code/senaabasz/notebookafacccaea8

