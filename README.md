# E-commerce Customer Review Analysis

## Project Overview

This project focuses on analysing customer reviews from a Women's E-Commerce Clothing dataset to understand customer satisfaction, product ratings, recommendation behaviour, and review patterns.

The analysis was performed using Python for data cleaning and exploratory data analysis (EDA), followed by Microsoft Power BI to build an interactive dashboard.

## Project Objectives

- Analyse customer ratings and review patterns.
- Understand customer recommendation behaviour.
- Explore ratings across different departments and divisions.
- Examine customer age distribution and positive feedback.
- Build an interactive Power BI dashboard to communicate key findings.

## Tools & Technologies

- **Python** – Data analysis and preprocessing
- **Pandas** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Exploratory data analysis
- **Microsoft Power BI** – Interactive dashboard development

## Dataset

**Dataset:** Women's E-Commerce Clothing Reviews

The dataset contains customer reviews and product-related information, including:

- Customer age
- Product ratings
- Review titles and review text
- Product department and division
- Product class
- Recommendation indicator
- Positive feedback count

## Data Cleaning & Preprocessing

The following preprocessing activities were performed:

- Inspected the dataset structure and data types.
- Identified missing values in relevant columns.
- Handled missing product category information.
- Reviewed missing values in review titles and review text.
- Prepared a cleaned dataset for further analysis.

## Exploratory Data Analysis

The following visualizations were created using Python:

1. Customer rating distribution
2. Customer age distribution
3. Recommended vs. not recommended reviews
4. Average rating by department
5. Average rating by division
6. Positive feedback distribution
7. Rating distribution across departments using boxplots

## Power BI Dashboard

An interactive Power BI dashboard was developed to explore customer review data through multiple report pages.

**Dashboard features include:**

- Key performance indicators (KPIs)
- Customer rating analysis
- Recommendation analysis
- Department and division comparisons
- Customer age analysis
- Positive feedback analysis

## Project Structure

```text
Ecommerce-Customer-Review-Analysis/
│
├── data/
│   └── processed/
│       └── Womens_Clothing_Cleaned.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── dashboard/
│   └── Ecommerce_Review_Analysis.pbix
│
├── visuals/
│   ├── main_dashboard.png
│   ├── product_review_analysis.png
│   └── customer_age
