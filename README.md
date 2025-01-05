# Supermarket Sales Analysis
## Overview
This project presents a comprehensive analysis of a supermarket sales dataset sourced from Kaggle. The dataset includes transactional data across three branches in different cities. Key objectives of the project include uncovering sales trends, understanding customer behavior, and providing actionable recommendations to optimize business performance.

## Key Features
- **Data Inspection:** Validation of data quality (duplicates, missing values, and data types).
- **Insightful Visualizations:** Clear and meaningful plots to highlight trends and patterns.
- **Actionable Recommendations:** Practical suggestions for improving sales and customer experience.

## Data Source
The dataset is available on [Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

## Project Workflow
### 1. Data Inspection and Cleaning
- Checked for duplicates, missing values, and negative values (none found).
- Parsed the date column as datetime for temporal analysis.

### 2. Exploratory Data Analysis (EDA)
- **Sales Overview:** Analyzed total sales, average sales per transaction, and branch-wise performance.
- **Product Line Analysis:** Identified top-performing product lines (Food and Beverages) and those with low sales (Health and Beauty).
- **Customer Insights:** Analyzed sales by customer type (Members vs. Non-members) and gender.
- **Temporal Trends:** Identified peak sales times (1900hrs and weekends).
- **Payment Methods:** Compared payment preferences across branches (Ewallet, Cash, Credit Card).
- **Ratings:** Evaluated customer satisfaction across branches and product lines.

### 3. Key Insights
- **Top-performing Branch:** Branch C slightly outperformed others in sales.
- **Sales Trends:** Sales peaked during weekends and lunchtime/evening hours.
- **High-performing Product Line:** Food and Beverages contributed the most to revenue.
- **Payment Preferences:** Ewallet was the most used payment method overall.
- **Ratings:** Branch B had lower ratings; Food and Beverages had the highest customer satisfaction.

### 4. Recommendations
- **Optimize Sales Timing:** Schedule promotions during peak hours (1300hrs and 1900hrs) and weekends.
- **Boost Product Lines:** Focus on marketing and improving Health and Beauty product sales.
- **Customer Retention:** Implement loyalty programs for Members and personalized discounts for Normal customers.
- **Improve Ratings:** Investigate Branch B’s lower ratings to enhance service quality.

## Project Structure
[**`Supermarket_Sales_Analysis.ipynb:`**](https://github.com/LabanMutua/Supermarket-Sales-Analysis/blob/main/Supermarket%20Sales%20Analysis.ipynb) Contains all steps from data inspection to EDA and final recommendations.

## Tools Used
- **Pandas:** Data manipulation and analysis.
- **Matplotlib & Seaborn:** Data visualization.
- **Jupyter Notebook:** Interactive coding and documentation.

## Future Work
- Develop predictive models to forecast sales trends.
- Explore clustering techniques for product grouping based on sales behavior.
