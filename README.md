# DSA-Data-Analysis-Capstone-Project

# Amazon Product Review Analysis
 Company Overview
This is RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon. I and my team has been tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

# Dataset Description
The dataset contains information scraped from Amazon product pages, including:
• Product details: name, category, price, discount, and ratings
• Customer engagement: user reviews, titles, and content
• Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
Total Records: 1,465 rows
TotalFields: 16 columns

# Analysis Tasks
Use pivot tables and calculated columns where necessary to answer the following:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200,
₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.
4. Final Task: Dashboard Creation
Using your cleaned dataset and pivot outputs, build an Excel dashboard. Unleash your
Creativity



# 1. Average Discount Percentage by Category

HomeImprovement	57.5%

Computers&Accessories	54.0%

Health&PersonalCare	53.0%

Electronics	50.8%

MusicalInstruments	46.0%

# 2. Number of Products Listed Under Each Category

Electronics	490

Home&Kitchen	448

Computers&Accessories	375

OfficeProducts	31

HomeImprovement	2

# 3. Total Number of Reviews Per Category

Electronics	15,778,848

Computers&Accessories	7,728,689

Home&Kitchen	2,991,069

OfficeProducts	149,675

MusicalInstruments	88,882

# 4. Top 5 Products by Average Rating

REDTECH USB-C to Lightning Cable	5.0

Syncwire Fast Charging Cable	5.0

Amazon Basics Wireless Mouse	5.0

Swiffer Instant Electric Water Heater Faucet	4.8

Oratech Coffee Frother electric	4.8

# 5. Average Actual Price vs Discounted Price by Category

Car&Motorbike	—	2,339.00

Computers&Accessories	—	842.65

Electronics	—	5,965.89

Health&PersonalCare	—	899.00

Home&Kitchen	—	2,330.62

# 6. Which products have the highest number of reviews?
Top 5 products by number of reviews:

AmazonBasics Flexible Premium HDMI Cable – 426,973 reviews

Amazon Basics High-Speed HDMI Cable, 6 Feet – 426,973 reviews

Amazon Basics High-Speed HDMI Cable (2-Pack) – 426,973 reviews

AmazonBasics Flexible Premium HDMI Cable (duplicate) – 426,972 reviews

boAt Bassheads 100 Wired Earphones – 363,713 reviews

# 7. How many products have a discount of 50% or more?
✅ 751 products

# 8. What is the distribution of product ratings?

Rating	Count
3.0	4

3.5	26

3.9	123

4.0	181

4.1	244

4.2	228

4.3	230

4.4	123

4.5	75
...	...
(A full detailed list is available if needed.)	

# 9. What is the total potential revenue (actual_price × rating_count) by category?
Top 5 categories by total potential revenue:

Smartphones – ₹38.5 billion

Smart Televisions – ₹25.4 billion

Smart Watches – ₹13.3 billion

In-Ear Headphones – ₹7.9 billion

USB Cables – ₹3.0 billion

# 10. Number of unique products per price range bucket:

Price Range	Unique Products
< ₹200	160

₹200–₹500	341

> ₹500	850

# 11. Rating vs. Discount Level
Correlation coefficient: -0.155

This indicates a weak negative relationship—as discounts increase, product ratings tend to slightly decrease, though the relationship isn't strong.

# 12. Products with Fewer Than 1,000 Reviews
Count: 326 products

A significant portion of the catalog hasn't received much public feedback yet.

# 13. Categories with the Highest Average Discounts
Top 5 based on average discount percentage:

Home Improvement – 57.5%

Computers & Accessories – 54.0%

Health & Personal Care – 53.0%

Electronics – 50.8%

Musical Instruments – 46.0%

These categories appear to be leveraging discounting heavily as a competitive tactic.





