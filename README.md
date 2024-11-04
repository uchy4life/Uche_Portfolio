# Uche_Portfolio
## Project 1. Sales Analysis
### Project Overview
This project involves a comprehensive analysis of chip sales data, using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization. The purpose is to uncover customer insights based on transactional data, identify significant purchasing patterns, and propose targeted marketing strategies.
### Data Import and Preparation

Two datasets: customer data and transaction data were imported into Jupyter notebook. After loading and exploring these datasets, I perform essential data cleaning steps:

Date Formatting: Converting date columns to a consistent date format to enable chronological analysis.
Outlier Removal: Identifying and removing any transactions with extreme quantities (such as those exceeding 200 units) to prevent data skewing.
There were no missing data 
### Exploratory Data Analysis (EDA)
In the EDA phase, I visualize and summarize sales trends over time, revealing a noticeable increase in chip purchases leading up to Christmas, followed by a drop on Christmas Day (due to store closures). This seasonal insight is valuable for understanding peak sales periods and planning stock or promotions.
![alt text](image.jpg)
### Feature Engineering
To enhance the dataset, I create two new features:
Pack Size: Extracting the chip pack size from product names.
Brand: Parsing product names to create a brand column, then standardizing brand names for consistency.
### Customer Segment Analysis
With the data prepped, I merge the customer and transaction datasets, allowing for segmentation analysis by customer life stage and spending category. Key metrics analyzed include:
Total Sales by Segment: Aggregating total sales by life stage and premium status reveals that sales are highest among "Budget - Older Families" and "Mainstream - Young Singles/Couples."
Customer Volume by Segment: Visualizing the number of customers per segment shows that mainstream young singles/couples and retirees dominate chip purchases.
Average Units and Price per Customer: Older and young families tend to buy more chips per transaction, while young singles/couples are more likely to pay a premium per packet.
### Customer Preferences Analysis
In addition to general spending patterns, I dive into brand and pack size preferences for a specific target segment, "Mainstream Young Singles/Couples." This segment shows:
A 23% higher likelihood to buy Tyrrells chips, and
A preference for 270g packs, with Twisties being a popular brand in this size.
### Conclusion and Recommendations
- This analysis identifies three key consumer segments for chips: Budget-conscious older families, Mainstream young singles/couples, and Mainstream retirees. The latter two segments, in particular, show higher average sales due to a larger customer volume and a tendency toward premium purchases.
- A targeted marketing strategy could focus on placing Tyrrells and smaller pack sizes in high-traffic areas frequented by young singles and couples to drive impulse purchases. By understanding the unique preferences of each segment, the company can better tailor its product placement and promotional efforts to boost overall category performance.
### Data Sources

