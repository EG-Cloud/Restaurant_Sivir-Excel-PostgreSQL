
# Project 1: Sales Performance Analysis for a Local Pizza Store

## Project Context & Objective

This project focuses on analyzing sales performance for a small local pizza shop, using historical order data. The main objective is to build an interactive Excel dashboard that provides meaningful business insights and answers key operational questions—such as identifying top-performing products, optimal selling times, and areas for improvement. The goal is to help the business make data-driven decisions to optimize sales and promotions.

## Data Source

The dataset used in this project is publicly available on Kaggle:  
**[Pizza Place Sales - Kaggle Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales)**

It includes multiple CSV files: `orders`, `order_details`, `pizzas`, and `pizza_types`.

## Approach & Tools

1. **Data Import & Structuring**:  
   The CSV files were first imported into pgAdmin4 (PostgreSQL). Foreign key relationships were defined between the tables to ensure data integrity.

2. **Data Cleaning**:  
   The dataset was cleaned to eliminate null values, fix inconsistent entries, and ensure the quality of all records. Unnecessary columns were dropped, and all time/date fields were standardized.

3. **Data Preparation**:  
   The cleaned tables were merged into a single dataset using SQL JOINs to create a comprehensive DataFrame with all relevant information: order time, pizza type, size, quantity, price, and category.

4. **Export to Excel**:  
   The final dataset was exported to Excel for dashboard creation. 

5. **Analysis in Excel**:  
   Using PivotTables, formulas, and slicers, KPIs and visualizations were built to highlight trends and answer business questions.

## Key Insights & Visualizations

The Excel dashboard provides clear visual breakdowns across months, categories, pizza types, and time of day. Key findings include:

- **Top-selling categories**:  
  - Classic and Supreme pizzas lead in sales.

- **Peak sales days**:  
  - Thursday, Friday, and Saturday generate the most revenue.  
  - (Opportunity: Launch promotions on low-performing days like Sunday and Monday.)

- **Sales by time of day**:  
  - Most sales occur in the afternoon (12:00–16:00) and evening (16:00–20:00).

- **Best months**:  
  - May and July are peak sales months, followed closely by January, March, and November.

- **Top 5 pizzas sold**:
  1. Thai Chicken Pizza  
  2. Barbecue Chicken Pizza  
  3. California Chicken Pizza  
  4. Classic Deluxe Pizza  
  5. Spicy Italian Pizza  

- **Bottom 5 pizzas (low performance)**:  
  - Spinach Pesto Pizza  
  - Mediterranean Pizza  
  - Spinach Supreme Pizza  
  - Green Garden Pizza  
  - Brie Carre Pizza  
  (Next step: Consider promotions or recipe revisions.)

- **Most popular sizes**:  
  - L, M, and S dominate customer preference.

The dashboard offers a flexible and interactive way for decision-makers to explore the data through filters (by month, pizza, category) and take informed action.
