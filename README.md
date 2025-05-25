Project: Netflix Movie and TV Show Analysis and Recommendation System

Project Overview
This project involved a comprehensive Exploratory Data Analysis (EDA), feature engineering, machine learning models, and content strategy recommendations based on movie and TV show datasets. We explored various aspects, including revenue, budget, popularity, and ROI trends, and built a machine learning-based recommendation system tailored for Netflix users.

Key Components and Work Done
1. Exploratory Data Analysis (EDA)
We performed detailed data exploration on the movies and TV shows datasets to uncover insights related to popularity, revenue, ratings, and other key variables:
Visualized Budget vs. Revenue Trends to identify successful budget ranges.
Revenue Optimization Analysis to explore high ROI movies.
Top 10 Popular and Top-Rated Movies and TV Shows by combining metrics like popularity and vote_average.
Identified Content Gaps by looking at underrepresented genres and languages.

2. Feature Engineering
We performed feature transformations to enhance model performance and insights:
Log transformation on budget and revenue for better skewed distribution handling.
Creation of derived features such as ROI (Return on Investment) and weighted scores to combine rating and popularity.

3. Machine Learning Models
Built machine learning models to improve user engagement and predict revenue:
Recommendation System:
Implemented a Random Forest-Based Recommendation Model based on genre preferences, popularity, and user ratings.
Recommended movies and TV shows based on content attributes.
Revenue Prediction Model:
Used Random Forest Regression to predict movie revenue based on features like budget, genre, and popularity.

Identified key revenue drivers.
4. Insights and Recommendations for Netflix Content Strategy
Based on our analysis, we provided actionable business insights, including:
Optimal Budget Recommendations: Suggested budget ranges that maximize ROI and revenue.
Content Gaps: Identified underrepresented genres, languages, and budget categories that could be potential areas for investment.
Low-Budget Success Factors: Highlighted factors (e.g., specific genres or audience engagement patterns) that help low-budget movies succeed.
Project Outcomes
Created visualizations and insights that Netflix (or any streaming platform) could use to optimize content creation and revenue generation.
Built and demonstrated a scalable Recommendation System to enhance user experience.
Provided a data-driven roadmap for content acquisition and budget allocation.


✅ Exploratory Data Analysis (EDA): Identified key trends in popularity, revenue, and budget efficiency.
✅ Recommendation System: Implemented a Random Forest-based model to recommend movies and TV shows based on content preferences.
✅ Revenue Prediction Model: Built a Random Forest Regression model to predict which movies generate the highest returns.
✅ Content Strategy Recommendations: Suggested optimal budget ranges, highlighted content gaps in genres/languages, and provided actionable insights for streaming success.
✅ Data Visualization: Created charts and dashboards to support better decision-making.

This project helped me sharpen my skills in EDA, feature engineering, machine learning, and business strategy.


---

## 📘 Project 2 Title: **Amazon’s Bestselling Books (2009–2019) Analysis**

---

### 🔍 Overview

This project is a comprehensive analysis of Amazon’s Top 50 Bestselling Books from 2009 to 2019. It follows the **Google Data Analytics Capstone Case Study** approach and utilizes both **Python (Google Colab)** and **Power BI** to uncover key trends, insights, and actionable business recommendations.



## 🔧 Tools Used

- **Python** (Google Colab): For data cleaning, preprocessing, and initial exploration  
- **Pandas, NumPy, Seaborn, Matplotlib**
- **Power BI**: For interactive dashboards and business-level storytelling
- **Excel**: Initial data review (optional)



## 🧭 Project Phases (Google Data Analytics Framework)



### 📌 1. Ask

**Business Task**:
> Analyze the bestselling books from 2009–2019 to uncover patterns in pricing, user ratings, genres, and revenue generation — enabling stakeholders to make better decisions on pricing, genre investment, and author selection.

**Key Questions**:
- What genres dominate bestseller charts?
- How do price and user ratings impact book success?
- Who are the most consistent top-performing authors?
- Which books generated the most estimated revenue?



### 📌 2. Prepare

- Dataset used: `bestsellers with categories.csv` from Kaggle
- Loaded and verified for consistency (no missing values, 550 rows total)
- Additional fields created: `Estimated Revenue = Price × Reviews`
- Saved cleaned dataset as `bestsellers_final_dataset.csv`



### 📌 3. Process

- Cleaned column names
- Checked and corrected data types (e.g., `Year` as integer)
- Removed duplicates
- Created new columns (Estimated Revenue)
- Handled outliers using visual checks (box plots)



### 📌 4. Analyze

**Key Findings from Python (Colab)**:
- Most books fall in the price range of **$5–$15**
- User ratings are heavily skewed toward **4.7–4.9**, indicating general user satisfaction
- Non-fiction has more variability in pricing than fiction
- Estimated revenue positively correlates with user rating and review count



### 📌 5. Share (Power BI Dashboards)

#### 📄 **Page 1 – Overview**
- KPI Cards: Total Books, Avg Price, Avg User Rating, Total Revenue
- Genre Distribution (Pie)
- Top Authors by Book Count

#### 📄 **Page 2 – Trends & Ratings**
- Avg Rating by Year (Line)
- Bestseller Count by Year (Line)
- Price & Rating Distributions (Histograms)
- Slicers: Genre, Year

#### 📄 **Page 3 – Revenue & Pricing**
- Top 10 Books by Revenue (Bar)
- Price vs Rating (Scatter)
- Avg Price by Author (Bar)
- Revenue by Genre (Stacked Column)

✅ **Interactive filters** allow stakeholders to explore trends by year, genre, and author.



### 📌 6. Act

**Recommendations**:
- Focus marketing on books with user ratings ≥ 4.8
- Set ideal pricing between **$10–$15** to maximize revenue
- Invest more in **Non-Fiction**, which shows high revenue variability and room for new bestsellers
- Encourage repeat publications from high-performing authors like Jeff Kinney and Stephen King

---





