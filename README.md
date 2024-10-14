![image](https://github.com/user-attachments/assets/0b5da75a-4eb4-4c8a-846b-441bff6ddbc8)

# Diwali Sales Analysis

This project analyzes Diwali sales data to uncover trends and insights about customer demographics, purchasing patterns, and sales performance across different states, age groups, and product categories.

## Overview

The Diwali Sales Analysis project aims to explore consumer behavior during the Diwali festival shopping season. The dataset used contains customer data, including gender, age, marital status, occupation, and sales details such as the number of orders and total amount spent.

## Key Libraries Used

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations.
- **Seaborn**: For statistical data visualization.

## Dataset

The dataset is imported from a CSV file: `Diwali Sales Data.csv`. It includes several columns, such as:

- **Gender**
- **Age Group**
- **Marital Status**
- **Occupation**
- **Product Category**
- **State**
- **Orders**
- **Amount**

## Data Cleaning and Preparation

The following steps were performed to clean and prepare the data for analysis:

- Dropped unrelated or blank columns (`Status` and `unnamed1`).
- Checked and handled missing values by removing rows with null values.
- Converted the data type of the `Amount` column from string to integer.
- Renamed the `Marital_Status` column to `Shaadi` for better readability.

## Exploratory Data Analysis (EDA)

The analysis included the following key areas:

### Gender
- A bar chart was plotted to show the distribution of buyers by gender.
- The purchasing power of females is higher compared to males.

### Age
- Buyers aged 26-35 years make up the largest group.
- A bar chart was used to show the age distribution of buyers by gender.

### State
- Top 10 states by the number of orders and total sales were identified. Uttar Pradesh, Maharashtra, and Karnataka were the leading states.

### Marital Status
- Married individuals, especially women, tend to purchase more, showing higher purchasing power.

### Occupation
- Most buyers work in IT, Healthcare, and Aviation sectors.

### Product Category
- Popular product categories include Food, Clothing, and Electronics.

### Top Products
- The most sold products by `Product_ID` were identified and visualized.

## Conclusion

Key insights from the analysis:

- **Demographic trends**: Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are more likely to purchase during Diwali.
- **Product preferences**: The top-selling categories are Food, Clothing, and Electronics.

## Thank You

This analysis helps in understanding consumer behavior during the Diwali season, which can guide businesses in making data-driven decisions for future campaigns.
