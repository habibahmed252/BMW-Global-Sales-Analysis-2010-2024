# BMW Global Sales Analysis \| 2010--2024 🏎️

An end-to-end **Data Analytics and Business Intelligence project**
analyzing **50,000 BMW sales records** across vehicle categories,
models, regions, fuel types, and other vehicle attributes from **2010 to
2024**.

The project combines **Python-based data cleaning and Exploratory Data
Analysis (EDA)** with an interactive **Power BI dashboard** to identify
sales patterns, revenue drivers, regional demand, fuel preferences, and
long-term performance trends.

------------------------------------------------------------------------

## 📌 Project Overview

The main objective of this project is to transform raw BMW sales data
into meaningful business insights that can support decisions related to:

-   Sales and revenue performance
-   Regional market demand
-   Vehicle category and model performance
-   Fuel-type preferences
-   Pricing and mileage patterns
-   Long-term sales trends

Rather than focusing only on dashboard development, the analysis answers
key business questions about **what drives sales, where demand is
strongest, and which vehicle categories and models contribute most to
overall performance**.

------------------------------------------------------------------------

## 🎯 Key Business Questions

1.  Which vehicle categories and models generate the highest sales
    volume and revenue?
2.  Which regions contribute most to BMW's overall sales performance?
3.  How do sales volumes change across the 2010--2024 period?
4.  How do fuel-type preferences vary across regions?
5.  How do vehicle categories compare in terms of price, mileage, and
    sales?
6.  Which models outperform others within their respective categories?
7.  What differences can be observed in customer preferences across
    markets?

------------------------------------------------------------------------

## 🎬 Dashboard Demo

[![BMW Power BI Dashboard
Demo]()

*Click the image above to watch the Power BI dashboard demonstration.*

------------------------------------------------------------------------

## Dashboard Preview

The Power BI report contains multiple interactive pages covering the
overall business performance and detailed analysis of each major vehicle
category.
<img width="1527" height="858" alt="image" src="https://github.com/user-attachments/assets/166a797e-e9bb-433e-a999-bd66284ee77a" />

### Overview Dashboard

![BMW Overview](<img width="1546" height="858" alt="image" src="https://github.com/user-attachments/assets/1a4267f9-0fce-444f-8b2c-d12228c33494" />


)

### M-Power Analysis

![BMW M-Power Analysis] M3 - M5
<img width="1564" height="864" alt="image" src="https://github.com/user-attachments/assets/f47d1710-d317-4da6-a2e6-aeb1064b1b36" />
<img width="1558" height="858" alt="image" src="https://github.com/user-attachments/assets/0c6c7fb5-244c-485a-a0d6-a435adab8496" />


### Sedan Analysis S3 - S5 - S7
<img width="1560" height="858" alt="image" src="https://github.com/user-attachments/assets/1b0aa610-1397-4e1f-ad46-80b9f6cf20b4" />
<img width="1564" height="858" alt="image" src="https://github.com/user-attachments/assets/f8ed88d0-a26e-4f0b-ab8f-014148a394ad" />
<img width="1564" height="859" alt="image" src="https://github.com/user-attachments/assets/cad09011-ea22-4a66-82cd-6f259fcfb40d" />

### EV & Hybrid Analysis

![BMW EV & Hybrid Analysis]i3 -i8
<img width="1561" height="864" alt="image" src="https://github.com/user-attachments/assets/0f4ef932-b3bc-45ee-a7d2-550f4834cab3" />
<img width="1561" height="859" alt="image" src="https://github.com/user-attachments/assets/977d464b-de47-4ea7-9396-3f1c559237f3" />


### SUV / X-Series Analysis

![BMW SUV / X-Series Analysis] X1 -X3 -X5 -X6
<img width="1561" height="859" alt="image" src="https://github.com/user-attachments/assets/5f2dd8b4-cb4f-455a-bdd7-769fa28081b6" />
<img width="1561" height="862" alt="image" src="https://github.com/user-attachments/assets/fa4966f7-db6b-4b1d-ac27-f508c9bf74d8" />
<img width="1564" height="862" alt="image" src="https://github.com/user-attachments/assets/6b1f24c3-ec19-4cc5-b6e2-953b97a6d4f5" />
<img width="1561" height="858" alt="image" src="https://github.com/user-attachments/assets/708ba81c-36f0-4deb-9d31-0a5c27454154" />


------------------------------------------------------------------------

## 📊 Dataset

### 📊 Dataset Summary

  -----------------------------------------------------------------------
  Attribute                           Description
  ----------------------------------- -----------------------------------
  Records                             50,000 sales records

  Time Period                         2010--2024

  Geographic Coverage                 Global

  Vehicle Categories                  SUV, Sedan, M-Power, EV & Hybrid

  Regions                             Asia, Europe, North America, South
                                      America, Middle East, Africa
  -----------------------------------------------------------------------

### Main Features

**Vehicle Information** - Vehicle Category - Model - Fuel Type -
Transmission - Engine Size - Color

**Sales & Financial Metrics** - Sales Volume - Revenue - Price - Mileage

**Geographical Information** - Region - Year

------------------------------------------------------------------------

## 🛠️ Data Analytics Workflow

### 1. Data Cleaning & Preparation --- Python

The raw dataset was cleaned and prepared using **Python and Pandas**.

Key preprocessing steps included:

-   Handling missing values
-   Removing duplicate records
-   Standardizing numerical data types
-   Converting price, mileage, engine size, and sales-related fields
    into usable numerical formats
-   Checking data consistency
-   Preparing the cleaned dataset for analysis and Power BI

### Example

``` python
import pandas as pd

# Load dataset
df = pd.read_csv("bmw_sales_data.csv")

# Handle missing values
df.dropna(subset=["Sales Volume", "Revenue"], inplace=True)

# Standardize numerical columns
df["Price"] = df["Price"].astype(float)
df["Mileage_KM"] = df["Mileage_KM"].astype(float)

# Export cleaned dataset
df.to_csv("bmw_cleaned_sales.csv", index=False)
```

### 2. Exploratory Data Analysis --- Python

EDA was performed to understand the structure and behavior of the
dataset before building the dashboard.

The analysis focused on:

-   Sales and revenue distributions
-   Category-level performance
-   Regional sales patterns
-   Fuel-type distribution
-   Model performance
-   Price and mileage distributions
-   Year-over-year sales trends

### 3. Business Intelligence --- Power BI

The cleaned dataset was imported into **Power BI** to build an
interactive multi-page dashboard.

#### Dashboard Pages

-   Home / Overview
-   M-Power Analysis
-   Sedan Analysis
-   EV & Hybrid Analysis
-   SUV / X-Series Analysis

#### Power BI Features Used

-   DAX measures
-   Power Query
-   Interactive slicers
-   KPI cards
-   Drill-down analysis
-   Bookmarks
-   Page navigation
-   Dynamic visuals
-   Category and model filters

------------------------------------------------------------------------

## Key Performance Indicators

  KPI                                    Value
  ----------------------- --------------------
  Total Sales Volume            **130M units**
  Total Revenue                    **\$9.71T**
  Average Vehicle Price     **\~\$74K--\$76K**
  Average Mileage                **\~100K KM**
  Dataset Size              **50,000 records**
  Analysis Period               **2010--2024**

**Important:** The **130M Total Sales Volume** is the sum of the
`Sales Volume` values across the 50,000 records. It represents
aggregated sales volume, not the number of transaction records.

------------------------------------------------------------------------

# 🔍 Key Insights

## 1. 🚙 SUV / X-Series is the strongest revenue contributor

The **SUV / X-Series category** generated approximately **\$3.53T in
total revenue** and around **47M in aggregated sales volume**, making it
the strongest-performing category in the dataset.

Among the analyzed models, **X5** generated the highest total revenue,
followed by **X3, X1, and X6**.

**Business implication:**\
The strong contribution of the SUV category highlights the importance of
maintaining a competitive SUV portfolio and closely monitoring the
performance of its leading models.

------------------------------------------------------------------------

## 2. 🚘 Sedan is another major contributor to overall performance

The **Sedan category** generated approximately **\$2.70T in revenue**
and around **36M in aggregated sales volume**.

Within the category, **Series 3 (s3)** and **Series 7 (s7)** performed
better than **Series 5 (s5)** based on the analyzed metrics.

**Business implication:**\
High-performing sedan models can serve as benchmarks when evaluating
product positioning, marketing focus, and inventory allocation within
the segment.

------------------------------------------------------------------------

## 3. 🌍 Asia and Europe are the strongest regional markets

Asia and Europe recorded the highest overall sales volumes in the
regional analysis.

Approximate aggregated sales volume:

-   **Asia:** \~22M
-   **Europe:** \~22M
-   **North America:** \~11M
-   **Other markets:** \~21M combined

The analysis also shows differences in vehicle-category and fuel-type
preferences across regions.

**Business implication:**\
Regional product allocation and marketing strategies can be adapted to
local demand rather than applying the same approach globally.

------------------------------------------------------------------------

## 4. ⚡ EV & Hybrid represents a significant part of the portfolio

The **EV & Hybrid category** generated approximately **\$1.82T in
revenue** and around **24M in aggregated sales volume**.

Within the category, **i8** generated higher total revenue than **i3**
in the analyzed dataset.

**Business implication:**\
Electrified vehicles represent a meaningful part of the analyzed
portfolio, making model-level performance an important factor when
evaluating future product strategies.

------------------------------------------------------------------------

## 5. 🏎️ M-Power is a significant performance segment

The **M-Power category** generated approximately **\$1.70T in revenue**
and around **23M in aggregated sales volume**.

The **M3** outperformed the **M5** based on the analyzed sales and
revenue measures.

**Business implication:**\
Performance-oriented models can make a substantial contribution to
overall revenue, so model-level performance should be considered when
planning marketing and inventory strategies.

------------------------------------------------------------------------

## 6. ⛽ Fuel-type preferences vary across regions

The regional analysis shows differences in fuel-type distribution:

-   **Diesel:** highest sales volume in South America
-   **Electric:** highest sales volume in North America
-   **Hybrid:** highest sales volume in Asia
-   **Petrol:** highest sales volume in Europe

**Business implication:**\
Fuel preferences are not uniform across markets. Regional strategies can
therefore consider the fuel mix that aligns with local demand patterns.

------------------------------------------------------------------------

## 7. 📅 Sales performance varies considerably over time

The 2010--2024 trend analysis shows noticeable year-to-year fluctuations
rather than a simple continuous growth pattern.

Category-level trends also differ:

-   **SUV:** strongest performance in 2024
-   **Sedan:** strongest performance in 2022
-   **M-Power:** strongest performance in 2022
-   **EV & Hybrid:** strongest performance in 2024

**Business implication:**\
Different vehicle categories follow different demand patterns.
Category-level forecasting and monitoring can therefore provide more
useful insights than looking only at total annual sales.

------------------------------------------------------------------------

## 8. 💰 Average vehicle prices remain relatively stable

Average vehicle prices across the major categories remain within a
relatively narrow range of approximately **\$74K--\$76K**.

This indicates that differences in total revenue are influenced strongly
by **sales volume and category scale**, rather than large differences in
average selling price.

**Business implication:**\
Within this dataset, improving sales volume in high-performing
categories may have a larger impact on total revenue than relying only
on price increases.

------------------------------------------------------------------------

# 💡 Business Recommendations

### 🌍 1. Develop region-specific strategies

Align product allocation and marketing activities with regional sales
and fuel-type preferences.

### 🚙 2. Prioritize high-performing SUV models

The strong revenue contribution of the SUV / X-Series category supports
continued attention to leading models such as **X5 and X3**.

### ⚡ 3. Monitor electrified vehicle performance

The EV & Hybrid category represents a substantial part of the analyzed
portfolio. Tracking individual model performance can help identify
opportunities for future product investment.

### 📈 4. Use category-level forecasting

Because different categories reach their strongest performance in
different years, forecasting should consider **vehicle category and
model level**, rather than relying only on total annual sales.

### 🎯 5. Optimize regional product allocation

Regional differences in category and fuel-type demand provide an
opportunity to tailor inventory and marketing decisions to local market
conditions.

------------------------------------------------------------------------

# 📁 Project Structure

``` text
BMW-Sales-Analysis/
│
│
├── images/
│   ├── home.png
│   ├── mpower_analysis.png
│   ├── sedan_analysis.png
│   ├── ev_analysis.png
│   └── suv_analysis.png
│
├── README.md
└── requirements.txt
```

------------------------------------------------------------------------

# 💻 Tech Stack

### Data Analysis

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn

### Business Intelligence

-   Microsoft Power BI
-   Power Query
-   DAX

### Documentation & Version Control

-   GitHub
-   Markdown

------------------------------------------------------------------------

# Project Takeaway

This project demonstrates a complete analytics workflow:

**Raw Data → Data Cleaning → EDA → Business Analysis → Power BI
Dashboard → Insights → Recommendations**

The goal was not simply to create visualizations, but to transform sales
data into **business-oriented insights** about product performance,
regional demand, customer preferences, and long-term sales trends.

------------------------------------------------------------------------

# Author

**Eng. Habiba Ahmed Talat**

