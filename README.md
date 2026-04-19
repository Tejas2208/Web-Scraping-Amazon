🛒 Amazon Sneaker Web Scraping & EDA
📌 Overview

This project focuses on extracting sneaker product data from Amazon and performing Exploratory Data Analysis (EDA) to uncover patterns in pricing, discounts, ratings, and customer behavior.

The goal is to move beyond raw data collection and generate actionable insights from real-world e-commerce data.

🎯 Problem Statement

E-commerce platforms like Amazon have thousands of sneaker listings, but there is no clear visibility into:

How pricing and discounts affect customer engagement
Whether higher-priced products receive better ratings
What drives product popularity (reviews, discounts, or branding)

This project attempts to answer these questions using scraped data.

🚀 Objectives
Scrape sneaker product data from Amazon
Clean and preprocess raw data
Perform univariate, bivariate, and multivariate analysis
Identify relationships between price, discount, ratings, and reviews
Generate insights useful for pricing and marketing decisions
🛠️ Tech Stack
Python
Requests, BeautifulSoup → Web Scraping
Pandas, NumPy → Data Processing
Matplotlib, Seaborn → Visualization
📂 Project Structure
Web-Scraping-Amazon/
│
├── data/                # Scraped dataset
├── notebooks/           # EDA notebook
├── src/                 # Scraping scripts
├── README.md            # Project documentation
🔍 Data Collection
Scraped sneaker product listings from Amazon (multiple pages)
Extracted features:
Product Title
Price
Original Price
Discount %
Rating
Review Count
ASIN (Product ID)
🧹 Data Cleaning
Removed missing and inconsistent values
Converted price and rating columns into proper formats
Created derived features (e.g., Discount %)
Checked for duplicates
📊 Exploratory Data Analysis
Univariate Analysis
Distribution of prices, ratings, and discounts
Bivariate Analysis
Price vs Discount
Price vs Rating
Rating vs Review Count
Multivariate Analysis
Correlation heatmap to identify relationships
📈 Key Insights
Strong positive correlation between original price and discounted price
Discounts reduce final price but do not guarantee higher ratings
Weak relationship between price and customer ratings
Highly rated products are not necessarily the most reviewed
Discounts have slight influence on review count (popularity)
⚠️ Challenges
Amazon anti-scraping restrictions
Dynamic HTML structure
Missing or inconsistent data
Data cleaning complexity
🧠 Conclusion

This project demonstrates how web scraping combined with EDA can reveal meaningful insights from e-commerce data. Pricing strategies and customer behavior are not always directly linked, highlighting the importance of deeper analysis.

🔮 Future Work
Use Selenium for dynamic scraping
Build an interactive dashboard (Power BI / Streamlit)
Apply machine learning for price prediction
Expand dataset across multiple product categories
