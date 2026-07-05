# 🏠 Airbnb Open Data Analysis

## 📌 Project Overview
This project explores the **Airbnb Open Data** dataset using Python.  
The goal is to analyze property types, neighborhood distribution, pricing trends, host activity, and review patterns.  
Visualizations are created with **Matplotlib**, **Seaborn**, and **Plotly** to uncover insights about Airbnb listings.

---

## ⚙️ Requirements
Install the following Python libraries before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn plotly openpyxl

Steps Performed in the Program

1. Data Loading
Uploaded the dataset (Airbnb_Open_Data.xlsx) using Google Colab’s file upload widget.

Loaded the Excel file into a Pandas DataFrame.

Converted the dataset into CSV format (Airbnb_Open_Data.csv) for easier handling.

2. Data Exploration
Displayed the first 5 rows using df.head().

Checked dataset structure and column details using df.info().

Identified missing values in columns like house_rules, license, and last review.

3. Property Type Analysis
Counted listings by room type (Entire home/apt, Private room, Shared room, Hotel room).

Visualized property type distribution with a bar chart.

4. Neighbourhood Group Analysis
Counted listings by neighbourhood group (Manhattan, Brooklyn, Queens, Bronx, Staten Island).

Found data inconsistencies (brookln, manhatan).

Visualized neighborhood group distribution with a bar chart.

5. Pricing Analysis
Calculated average price per listing across neighborhood groups.

Visualized average prices with bar charts.

Analyzed average price trends by Construction year.

6. Host Analysis
Identified top 10 hosts by calculated host listings count.

Visualized host activity with bar charts.

7. Review Analysis
Compared average review rate between verified and unconfirmed hosts.

Grouped review rates by neighbourhood group and room type.

Visualized review patterns with grouped bar charts.

8. Correlation Studies
Calculated correlation between price and service fee (~0.9999).

Created regression plots for:

Price vs. Service Fee

Host listings count vs. Availability

9. Visualizations Created
Bar Charts: Property types, neighborhood groups, host activity.

Line Charts: Average price trends by construction year.

Regression Plots: Price vs. Service Fee, Listings vs. Availability.

Grouped Bar Charts: Review rates by neighborhood and room type.

10. key Insights
Manhattan & Brooklyn dominate Airbnb listings.

Entire homes/apartments are the most common property type.

Service fee is almost perfectly correlated with price.

Verified hosts tend to have slightly better review scores.

Some data inconsistencies exist (e.g., misspelled neighborhood groups like brookln, manhatan).

11. Future Work
Data Cleaning: Correct misspelled neighborhood names and handle missing values.

Predictive Modeling: Build machine learning models to predict listing prices based on features.

Sentiment Analysis: Analyze guest reviews for deeper insights into satisfaction.

Interactive Dashboards: Use Plotly or Tableau for dynamic exploration.

12. License
This project is for educational and research purposes only.
Dataset belongs to Airbnb Open Data contributors.
