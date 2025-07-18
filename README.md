# Amazon Product Analysis

## 📌 Objective
To analyze 1,465 Amazon products across categories and uncover trends in pricing, discounts, reviews, and ratings. 

## 📁 Dataset
- Source: Amazon product page scraping (shared via LMS)
- Rows: 1,465
- Columns: 16 fields including price, discount, reviews, etc.

## 🔍 Key Questions Answered (Q1–Q14)
- Average discount by category
- Product count per category
- Total reviews by category
- Highest rated products
- Actual vs. discounted price by category
- Products with highest number of reviews
- Count of products with ≥50% discount
- Distribution of product ratings
- Potential revenue by category
- Product count by price bucket
- Relation between rating and discount
- Products with <1,000 reviews
- Categories with highest discounts
- Top 5 products based on rating × review count

#### 📁 Project Contents
        Sheet Name	Description
        amazon_rawsheet	Original Amazon dataset with 1,465 rows and 16 columns.
        
        Cleaned Data	Preprocessed data with corrected formats, missing values handled, and unnecessary fields removed.
        
        Pivot_Q1-3, Pivot_Q5 Pivot tables analyzing pricing, average discounts, and bestsellers.
        
        Pivot_Q4_Q6        Q4 Identifies top-rated products by category and rating count.
        
                           Q6	Analysis of rating_count vs average_rating.
        
        Q7_Filter	Filtered view showing only products with ≥50% discount.
        
        Pivot_Q8-Q10	Pivots and Visualizations covering pricing distribution, sub-category insights, and discounts.
        
        Q11_Chart
        
        Q12_Filter	Summary view of review vs rating trend.
        
        Pivot_Q13, Q14_Filter, Q14_Top5Products
        
        Dashboard	Final compiled dashboard with key visuals and insights.

## 🧠 Key Insights
- USB Cables had the highest average discount (~65%)
- 891 products had fewer than 1,000 reviews
- No clear correlation between discount and rating
- Top 5 products include brands like MI, boAt, TP-Link
- ₹200–₹500 was the most common price range

## 🛠 Tools Used
    Google Sheets
    Pivot Tables
    Scatter, Column & Pie Charts
    Data Cleaning Techniques

## 📊 Dashboard
Find it attached in the analysis file.

---

Created by: Hephzibah Oluwatimilehin (Beginner Techie)
