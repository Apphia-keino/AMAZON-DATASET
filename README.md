# E-Commerce Sales Data Analysis

## Overview
This project analyzes an Amazon e-commerce dataset using **MySQL for database management** and **Python (Pandas, Matplotlib, Seaborn) for data analysis and visualization**. The goal is to extract business insights that can help improve sales and customer engagement.

## Dataset Description
The dataset contains information about Amazon products, including:
- **Product Name**
- **Category**
- **Rating and Rating Count**
- **Actual Price and Discounted Price**
- **Discount Percentage**

## Project Workflow

### Part 1: Data Preprocessing in Python
- **Load Dataset**: Import `amazon.csv` into Pandas.
- **Data Cleaning**:
  - Convert `discounted_price` and `actual_price` to numerical format.
  - Convert `rating_count` to integer format.
  - Extract primary product categories.
  - Compute the `discount_amount`.

### Part 2: MySQL Database Integration
- **Create a MySQL Database (`ecommerce_db`)**.
- **Create and Populate Table (`products`)**.
- **Execute SQL Queries for Analysis**:
  - Top 10 most reviewed products.
  - Category with the highest average rating.
  - Products with a discount greater than 50%.
  - User who has written the most reviews.
  - Top 5 best-selling categories.

### Part 3: Data Analysis in Python
- **Exploratory Data Analysis (EDA)**:
  - Distribution of ratings.
  - Correlation between discount percentage and rating.
  - Top-selling product categories.
  - Relationship between discount and rating count.
- **Data Visualization**:
  - Histogram for ratings distribution.
  - Scatter plot for discount percentage vs. rating.
  - Pie chart for top-selling categories.
  - Heatmap for correlations between numerical columns.

### Part 4: Business Insights
- Identify categories that should be prioritized for discounts.
- Suggest strategies to improve sales and customer engagement.
- Highlight anomalies or interesting patterns found in the data.

## Tools and Libraries Used
The project utilizes a range of tools and libraries for data analysis and visualization:

### **Data Analysis and Manipulation:**
- ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### **Database Management:**
- ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### **Visualization:**
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
- ![Seaborn](https://img.shields.io/badge/Seaborn-5B6EA6?style=for-the-badge&logo=python&logoColor=white)

## How to Run the Project
Before you begin, ensure you have Python 3.8 or later installed on your machine. Follow these steps to set up and run the project:

### **1. Clone the Repository:**
```sh
 git clone https://github.com/your-repo/ecommerce-sales-analysis.git
 cd ecommerce-sales-analysis
```

### **2. Install Dependencies:**
```sh
 pip install -r requirements.txt
```

### **3. Set Up MySQL Database:**
- Create a database `ecommerce_db` in MySQL.
- Run the provided SQL script to create tables and insert data.

### **4. Run the Jupyter Notebook:**
```sh
 jupyter notebook
```
Open `Ecommerce Sales Analysis Notebook.ipynb` and execute the cells step by step.

## Files Included
- **Jupyter Notebook (`Ecommerce Sales Analysis Notebook.ipynb`)**: Contains Python code for data processing, analysis, and visualization.
- **SQL Script (`Ecommerce Sales Analysis Sql.sql`)**: Contains MySQL database setup and queries.
- **README.md**: Summary of project details and insights.


---
**Author:** Apphia Keino

