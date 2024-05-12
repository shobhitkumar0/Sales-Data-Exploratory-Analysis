#Sales Data Analysis

## Overview
This project analyzes the Diwali sales data to uncover insights into customer purchasing patterns. The dataset contains 11,251 entries and 15 features, focusing on customer demographics and order details.

## Data Preprocessing
The data was cleaned by dropping missing values and converting the 'Amount' column to integer data type for accurate calculations.

## Exploratory Data Analysis (EDA)
The EDA focused on various aspects such as gender, age group, state, marital status, occupation, and product category to understand the sales trends.

### Gender Analysis
- A bar chart was plotted to count the number of purchases made by each gender.
- Another bar chart displayed the total amount spent by each gender, indicating higher spending by females.

### Age Analysis
- The age group distribution was visualized, highlighting that most buyers belong to the 26-35 years age group.
- Total amount spent by each age group was also analyzed, with the same age group (26-35 years) spending the most.

### State Analysis
- The top 10 states by the number of orders were visualized, showing Uttar Pradesh, Maharashtra, and Karnataka leading in orders and sales.

### Marital Status Analysis
- The marital status of buyers was plotted, revealing that married women have a higher purchasing power.

### Occupation Analysis
- The occupation distribution showed that most buyers work in IT, Healthcare, and Aviation sectors.

### Product Category Analysis
- The most sold product categories were Food, Clothing, and Electronics.

## Conclusion
The analysis concluded that married women in the age group of 26-35 years from UP, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are more likely to purchase products from Food, Clothing, and Electronics categories.

## How to Run the Analysis
To run this analysis, ensure you have `pandas`, `matplotlib`, and `seaborn` installed in your Python environment. Use the following commands to install these libraries if you haven't already:

```bash
pip install pandas matplotlib seaborn

Then execute the analysis.py file.
