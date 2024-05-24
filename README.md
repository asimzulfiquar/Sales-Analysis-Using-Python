Sure! Below is a detailed README file for your project:

---

# Diwali Sales Analysis

## Overview

This project involves analyzing Diwali sales data to uncover insights about purchasing behavior. The analysis covers various dimensions such as gender, age group, state, marital status, occupation, and product categories. The goal is to identify key trends and patterns that can inform marketing strategies and business decisions.

## Dataset

The dataset used in this analysis contains information about Diwali sales transactions, including attributes like gender, age group, state, marital status, occupation, product category, and amount spent. The dataset was read from a CSV file.

## Data Cleaning

The initial dataset contained some unrelated columns and null values. The data cleaning steps included:
1. Dropping the 'Status' and 'unnamed1' columns.
2. Removing rows with null values.
3. Converting the 'Amount' column to integer type.

## Exploratory Data Analysis (EDA)

### Gender Analysis

1. **Gender Count**:
   - A bar chart was plotted to show the count of buyers by gender.
   - It was observed that females constituted the majority of buyers.

2. **Gender vs Total Amount**:
   - A bar chart was plotted to show the total amount spent by gender.
   - Females had a higher purchasing power compared to males.

### Age Group Analysis

1. **Age Group Count by Gender**:
   - A count plot was created to show the distribution of buyers across different age groups, segmented by gender.
   - The age group 26-35 had the highest number of buyers, with females being the predominant buyers in this group.

2. **Total Amount vs Age Group**:
   - A bar chart was plotted to show the total amount spent by different age groups.
   - The age group 26-35 had the highest total amount spent.

### State Analysis

1. **Number of Orders by State**:
   - A bar chart was plotted to show the top 10 states by the number of orders.
   - Uttar Pradesh, Maharashtra, and Karnataka were the top three states.

2. **Total Sales by State**:
   - A bar chart was plotted to show the top 10 states by total sales amount.
   - Uttar Pradesh, Maharashtra, and Karnataka were the top three states.

### Marital Status Analysis

1. **Marital Status Count**:
   - A count plot was created to show the number of buyers by marital status.
   - Most buyers were married.

2. **Marital Status vs Total Amount by Gender**:
   - A bar chart was plotted to show the total amount spent by marital status, segmented by gender.
   - Married women had the highest purchasing power.

### Occupation Analysis

1. **Occupation Count**:
   - A count plot was created to show the distribution of buyers across different occupations.
   - Most buyers were working in IT, Healthcare, and Aviation sectors.

2. **Occupation vs Total Amount**:
   - A bar chart was plotted to show the total amount spent by different occupations.
   - Buyers from IT, Healthcare, and Aviation sectors had the highest total amount spent.

### Product Category Analysis

1. **Product Category Count**:
   - A count plot was created to show the number of products sold in different categories.
   - Food, Clothing, and Electronics were the most sold product categories.

2. **Product Category vs Total Amount**:
   - A bar chart was plotted to show the total amount spent on different product categories.
   - Food, Clothing, and Electronics had the highest total sales amount.

3. **Top 10 Most Sold Products**:
   - A bar chart was plotted to show the top 10 most sold products by the number of orders.
   - This provided insights into the specific products driving sales.

## Conclusion

From the analysis, the key findings are:
- Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the primary consumers.
- The most popular product categories are Food, Clothing, and Electronics.

## Usage

To replicate this analysis, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/diwali-sales-analysis.git
   ```
2. Navigate to the project directory:
   ```
   cd diwali-sales-analysis
   ```
3. Install the required libraries:
   ```
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the analysis script:
   ```
   python analysis.py
   ```

## Acknowledgements

This project was completed as a part of my data analysis learning journey. The dataset was provided for educational purposes.

---

Feel free to customize this README further based on any additional details or preferences you have!
