# Google Play Store Apps & Reviews Analysis

## About the Dataset
**Data Source:**  
App and review data was scraped from the Google Play Store by Lavanya Gupta in 2018. Original files listed [here](https://www.kaggle.com/lava18/google-play-store-apps).

## Overview
This project involves the analysis of Google Play Store apps and reviews, focusing on data cleaning, exploratory data analysis (EDA), and visualization to derive insights about app ratings, sizes, reviews, content ratings, installations, pricing, and revenue estimates.

## Key Steps and Findings

### Data Cleaning
- **Removed Unnecessary Columns:** Dropped columns like `Last_Updated` and `Android_Ver`.
- **Handled Missing Values:** Removed rows with missing values.
- **Removed Duplicates:** Identified and removed duplicate entries.

### Analysis and Insights
1. **Highest Rated Apps:** Identified the top-rated apps.
2. **Largest Apps by Size:** Analyzed the largest apps by size (MB).
3. **Most Reviewed Apps:** Listed the apps with the highest number of reviews.
4. **Content Ratings Visualization:** Created pie and donut charts to visualize content ratings distribution.
5. **Installations Data Conversion:** Converted `Installs` column to numeric for analysis.
6. **Revenue Estimates:** Calculated revenue estimates and identified the top-grossing paid apps.
7. **Category Analysis:** Visualized app counts and installs by category using bar charts and scatter plots.
8. **Genre Analysis:** Analyzed nested genre data after separating it.
9. **Free vs. Paid Apps:** Compared the number of free vs. paid apps across categories.
10. **Download Comparison:** Compared downloads for free versus paid apps using box plots.
11. **Revenue by Category:** Analyzed revenue by app category with box plots.
12. **Pricing Strategies:** Examined pricing strategies for paid apps across categories.

### Conclusion
- This project provides insights into various aspects of Google Play Store apps, including ratings, sizes, reviews, content ratings, installations, pricing, and revenue. The visualizations and analyses help understand the distribution and characteristics of different app categories and types.

### Future Work
1. Further analysis of user reviews to understand sentiment.
2. Detailed analysis of app performance over time.
3. Correlation analysis between app features and user ratings
