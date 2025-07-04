# DSA DATA ANALYSIS EXCEL PROJECT 
## Project Title: Amazon Product Review Analysis Report
### Project Overview
This project aimed to conduct a comprehensive exploratory data analysis (EDA) of Amazon product and customer review data.
The main objective was to generate actionable insights for Retail Tech Insights' e-commerce clients, to specifically enhance product improvement, provide a well refined marketing strategies, and optimize customer engagement.

### Data Source
The data was meticulously scraped from Amazon product pages. 
It comprises 1,465 product records, consisting of 16 columns of information related to product details (name, category, price, discount, ratings) and customer engagement metrics (user reviews, titles, and content).

### Tools Used
Pivot tables and Calculated columns were explicitly used to analyze the data to provide useful insight and draw inference.

### Data Cleaning and Preparation
In the process of Data cleaning, I deleted duplicate Product ID, making the product ID distinct for each data record, then initial data processing was performed, resulting to 1,351 unique products. This involved handling missing values or inconsistencies to ensure data readiness for analysis.

### Exploratory Data Analysis (EDA)
The EDA phase involved addressing 14 specific business questions through data aggregation, filtering and calculation. This included examining discount distributions, product counts, review counts, rating patterns, price comparisons, and total potential revenue across various product categories. The analysis also explored the relationship between product ratings and discount levels.

### Data Analysis
The analysis provides a comprehensive overview of product performance, pricing strategies, and customer engagement across Amazon product categories. Key findings include:
-	Discount Landscape: Home Improvement, Computers & Accessories and Health & Personal Care shows the highest average discounts (of 58% and approx. 53%), with Toys & Games having no average discount. The highest individual discounts observed were in Computers & Accessories (94%), Electronics (91%), and Home & Kitchen (90%). Also, a total of 662 products are offered with a discount of 50% or more.
-	Category Dominance: Electronics, Home & Kitchen, and Computers & Accessories are the largest categories by product count, review count, and potential revenue. Electronics, in particular, demonstrates exceptionally high review counts (14.2 million) and potential revenue (approx. $91.32 billion).
-	Pricing Overview: The overall average actual price is $5,691.18, with an average discounted price of $3,304.80. Most products (850) fall into the > ₹500 price range.
-	Rating Insights: Most products are rated between 4.1 and 4.3, suggesting general customer satisfaction. There is no clear linear correlation observed between discount levels and average product ratings. Office Products and Toys & Games show the highest average ratings (4.31 and 4.30 respectively).
-	Product Engagement: 310 products have received fewer than 1,000 reviews, indicating a segment with lower customer engagement.
-	Top Product: A top-performing product identified based on combined rating and reviews is: Electronics > Home Theater, TV & Video > Accessories > Cables.

### Result Finding
The analysis highlights categories with high potential revenue and customer interaction such as Electronics, Computer and Accessories as well as areas needing attention, such as products with low review counts or no discounts like Toys and Games, Musical Instruments.

### Recommendation
Based on these findings, it is recommended that Retail Tech Insights' clients:
-	Focus on High-Performing Categories: Prioritize marketing and product development efforts in Electronics, Computers & Accessories, and Home & Kitchen due to their high product counts, review counts, and revenue potential.
-	Optimize Discount Strategies: Review the discount strategies for categories like Toys & Games that currently show no discounts, and evaluate if strategic discounting could boost sales or engagement.
-	Enhance Engagement for Low-Review Products: Implement strategies to increase reviews for the 310 products with fewer than 1,000 reviews, as higher review counts often correlate with increased sales and visibility.
-	Leverage High-Discount Appeal: Utilize the high discount percentages in categories like Computers & Accessories and Electronics in marketing campaigns to attract price-sensitive customers.
-	Deep Insights into Specific Products: Further investigate top-performing products (like the identified Electronics cable) to understand their success factors and replicate them where possible.
