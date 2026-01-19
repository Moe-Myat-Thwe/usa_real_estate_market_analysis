# 📊 Data Analytics Project – End-to-End Market Analysis
## 📌 Overview

This project demonstrates a complete data analytics workflow, from raw data exploration to business-ready insights.
The goal is to analyze a real-world dataset, clean and transform the data using Python, and communicate insights through an interactive Power BI dashboard, a written report, and a presentation created with Gamma.

The project focuses on:

- Understanding data structure and quality

- Identifying key patterns and relationships

- Translating analysis into clear, stakeholder-friendly insights

## 📁 Dataset

- Source: https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset

- Key features include:

  - Numeric variables ( price, house_size, acre_lot, bed, bath)

  - Categorical variables (brokered by, status)

  - Location variables(street, city, state, zip_code)

  - Date(prev_sold_date)


## 🛠 Tools & Technologies

- Python – Data loading, EDA, and cleaning

  - Libraries: pandas, numpy

- Power BI – Data modeling, DAX measures, interactive dashboard

- Gamma – Presentation deck for executive-level storytelling

- GitHub – Version control and project documentation

## 🔍 Project Steps
### 1. Data Loading

- Loaded the dataset using Python (pandas)

- Inspected schema, data types, and missing values


### 2. Exploratory Data Analysis (EDA)

- Summary statistics and distributions

- Identification of outliers and extreme values

- Relationship analysis between key variables


### 3. Data Cleaning & Preparation

- Handled missing and invalid values

- Standardized data types and column names

- Created derived metrics for analysis

- Flagged extreme values instead of removing them to preserve data integrity


### 4. Power BI Dashboard

- Built an interactive, one-page dashboard

- Created KPI cards, maps, bar charts, scatter plots, and filters

- Used DAX to calculate medians, distributions, and category-level insights

### 5. Reporting & Presentation

- Wrote a structured project report summarizing insights and findings

- Created a professional presentation deck using Gamma for stakeholders

## 📊 Dashboard

The Power BI dashboard provides:

- High-level KPIs for quick market understanding

- Geographic distribution analysis

- Top categories and ranking views

- Relationship analysis using scatter plots and trend lines

- Interactive slicers for flexible exploration

- The dashboard is designed for executive and analyst audiences.

## 📈 Key Results

- Identified clear variation in key metrics across categories and locations

- Revealed relationships between size-related variables and pricing behavior

- Highlighted dominant market segments versus smaller, high-impact segments

- Demonstrated how outliers influence perception and why transparent handling matters

## ▶️ How to Run
### Python Analysis

1. Clone the repository

2. Install dependencies:

       pip install pandas numpy 


3. Run the notebook or Python script to reproduce EDA and cleaning steps

### Power BI

1. Open the .pbix file in Power BI Desktop

2. Refresh data if needed

3. Interact with filters and visuals

