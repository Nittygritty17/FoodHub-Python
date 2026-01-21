# FoodHub Data Analysis - Introduction to Python

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-440154?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

**Course Project: Introduction to Python**  
Performed exploratory data analysis (EDA) on FoodHub orders to uncover demand patterns for restaurants and cuisines, enabling better customer experience and business decisions.

## 📊 Project Overview
- **Dataset**: 1,898 orders across 178 restaurants and 14 cuisines (e.g., American: 584 orders, Japanese: 470).
- **Key Focus**: Univariate/multivariate analysis of order cost, preparation/delivery time, ratings, and day-of-week trends.


## 🔍 Key Insights
| Insight | Value/Details |
|---------|---------------|
| Dataset Shape | 1,898 rows × 9 columns |
| Food Prep Time | Min: 20 min, Mean: 27.37 min, Max: 35 min|
| Unrated Orders | 736 (38.8%) |
| Top Cuisine (Weekend) | American (415 orders) |
| Orders > $20 | 555 (29.24%) |
| Mean Delivery Time | 24.16 min |
| Top 3 Customers | ID 52832 (13 orders), 47440 (10), 83287 (9) |
| Top 5 Restaurants | Shake Shack (219), The Meatball Shop (132), Blue Ribbon Sushi (119), etc.|

## 📈 Visualizations
- Histograms/Boxplots: Cost, prep/delivery time distributions.
- Countplots: Cuisine/restaurant popularity.
- Heatmaps: Correlations (cost vs. time vs. rating).
- Subplots: Multivariate trends by day/rating.

## 📁 Files
- `FoodHub_IntroToPython.ipynb` - Full EDA notebook.
- `foodhub_order.csv`


## 💡 Business Recommendations
- Promote American cuisine on weekends for higher demand.
- Target top customers (e.g., ID 52832) with 20% vouchers.
- Optimize prep for high-cost orders (> $20).
