# Zomato India — Restaurant Intelligence Analysis

## Overview
An end-to-end data analysis project exploring restaurant trends across 
India's top 100 cities using Zomato data scraped in October 2023. 
The project covers data cleaning, exploratory data analysis, and 
an interactive Power BI dashboard.

## Dataset
- **Source:** Zomato India (scraped using Selenium, October 2023)
- **Kaggle:** [Zomato Data — 40K Restaurants of India's 100 Cities](https://www.kaggle.com/datasets/rrkcoder/zomato-data-40k-restaurants-of-indias-100-cities)
- **Size:** 44,724 restaurants across 100 cities
- **Columns:** Restaurant Name, Rating, Cuisine, Average Price, Average Delivery Time, Safety Measure, Location

## Tools & Technologies
- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook/ VS Code** — Analysis and EDA
- **Power BI** — Interactive dashboard
- **Git** — Version control

## Project Structure
```
zomato-analysis/
├── data/
│   ├── zomato_dataset.csv        # Raw dataset
│   └── zomato_cleaned.csv        # Cleaned dataset
├── notebooks/
│   ├── 01_data_overview.ipynb    # Initial data exploration
│   ├── 02_data_cleaning.ipynb    # Data cleaning & preprocessing
│   ├── 03_eda.ipynb              # Exploratory data analysis
│   └── 04_deep_analysis.ipynb   # Deep dive analysis
├── visuals/                      # All generated charts
├── dashboard/
│   └── zomato_dashboard.pbix    # Power BI dashboard
└── README.md
```

## Key Findings
- **North Indian** cuisine dominates with 1,973 restaurants — nearly double the next category
- **Ice Cream & Desserts** is the highest rated cuisine (4.33 avg) despite not being the most common
- **NCR** has the highest average price per person (₹221) while **Kanpur** is the most affordable (₹164)
- **Kolkata** has the most restaurants (1,296) but **Hyderabad** has the highest average rating (4.04)
- **Price and delivery time have minimal impact on ratings** — customer satisfaction is consistent across all price and speed categories
- **59.6%** of restaurants follow Max Safety measures

## Dashboard Pages
1. **Overview** — KPI cards, rating distribution, top cities, safety measure breakdown
2. **City Analysis** — Restaurant count, pricing, ratings and delivery time by city
3. **Cuisine Analysis** — Top cuisines by count, rating, price and delivery time

## How to Run
1. Clone the repo
2. Install dependencies:
```
pip install pandas numpy matplotlib seaborn jupyter squarify
```
3. Run notebooks in order (01 → 02 → 03 → 04)
4. Open `dashboard/zomato_dashboard.pbix` in Power BI Desktop

## Author
**Atharva Dange**  
[LinkedIn](https://linkedin.com/in/atharva-dange) | [GitHub](https://github.com/Danthr)