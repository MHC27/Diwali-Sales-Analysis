# Diwali Sales Analysis

This project aims to analyze sales data from a Diwali festival sales event. The primary objectives are to understand customer purchasing behavior, identify trends, and generate actionable insights for business decision-making.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Research Questions](#research-questions)
- [Workflow](#workflow)
- [Analysis and Results](#analysis-and-results)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

The Diwali Sales Analysis project investigates sales transactions during the Diwali festival, aiming to uncover patterns in consumer behavior, product popularity, and demographic influences on sales performance. The analysis helps businesses optimize marketing strategies and inventory management for future festivals.

## Data Source

The dataset used is a collection of sales data from a retail store during the Diwali festival season. Typical columns include:

- User_ID
- Product_ID
- Gender
- Age
- Occupation
- City_Category
- Product_Category
- Purchase Amount

> **Note:** The actual dataset used is available in the [`data/`](data/) directory.

## Research Questions

1. What are the key demographic factors influencing Diwali sales?
2. Which product categories are most popular during the festival?
3. How do purchasing patterns vary by city, age, and gender?
4. What marketing strategies can be derived from the analysis?

## Workflow

1. **Data Collection**  
   - Gathered Diwali sales data from CSV file(s).
2. **Data Cleaning**  
   - Removed null values and duplicates.
   - Standardized column names and data types.
   - Handled missing or inconsistent entries.
3. **Exploratory Data Analysis (EDA)**  
   - Generated statistical summaries.
   - Visualized distributions and relationships among variables.
4. **Data Visualization**  
   - Created bar charts, histograms, and pie charts for demographic and sales variables.
   - Used heatmaps to analyze correlations.
5. **Insight Generation**  
   - Identified trends, patterns, and outliers.
   - Answered research questions based on the analysis.

## Analysis and Results

- Performed descriptive statistics to understand sales distribution.
- Analyzed purchase patterns by gender, age group, and city category.
- Compared product category performance.
- Investigated the impact of occupation and marital status on sales.

## Visualizations

Sample visualizations created during the analysis include:

- **Sales by Age Group:**
  ![Sales by Age Group](images/sales_by_age.png)
- **Product Category Popularity:**
  ![Product Category Popularity](images/product_category.png)
- **Sales Distribution by City:**
  ![Sales by City](images/sales_by_city.png)

(Note: Replace image paths if you have your own plots.)

## Key Insights

- **Demographics:**  
  Female customers in the age group of 26-35 made the highest number of purchases.
- **City Trends:**  
  Tier-1 cities saw the highest sales, possibly due to higher disposable incomes.
- **Product Trends:**  
  Electronics and apparel were the most popular categories.
- **Marketing Recommendations:**  
  Targeted campaigns toward young urban professionals could boost future sales.

## Conclusion

The Diwali Sales Analysis provides actionable insights for retail businesses to understand their customer base and optimize sales strategies for festival campaigns. With data-driven recommendations, businesses can enhance their marketing efforts and inventory planning.

## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV/Excel Data Files

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/MHC27/Diwali-Sales-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Diwali-Sales-Analysis
   ```
3. Open the analysis notebook (e.g., `Diwali_Sales_Analysis.ipynb`) in Jupyter Notebook or Jupyter Lab.
4. Run all the cells to reproduce the analysis.

## Acknowledgements

- Dataset Source: [Kaggle](https://www.kaggle.com/datasets) or internal company data
- Inspired by various open-source data analysis projects
