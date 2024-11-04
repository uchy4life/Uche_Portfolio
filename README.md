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
- I visualize and summarize sales trends over time, revealing a noticeable increase in chip purchases leading up to Christmas, followed by a drop on Christmas Day (due to store closures). This seasonal insight is valuable for understanding peak sales periods and planning stock or promotions.
![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown.png)     ![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown)

### Feature Engineering
To enhance the dataset, I create two new features:
Pack Size: Extracting the chip pack size from product names.
Brand: Parsing product names to create a brand column, then standardizing brand names for consistency.
### Customer Segment Analysis
With the data prepped, I merge the customer and transaction datasets, allowing for segmentation analysis by customer life stage and spending category. 

![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown-2)

#### Key metrics analyzed include; 

**Total Sales by Segment**: Aggregating total sales by life stage and premium status reveals that sales are highest among "Budget - Older Families" and "Mainstream - Young Singles/Couples."

![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown-3)

**Customer Volume by Segment**: Visualizing the number of customers per segment shows that mainstream young singles/couples and retirees dominate chip purchases.

![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown-4)

**Average Units per Customer**: Older and young families tend to buy more chips per transaction, while young singles/couples are more likely to pay a premium per packet.

![alt text](https://github.com/uchy4life/Uche_Portfolio/blob/main/Unknown-5)

**Average price per unit**: Mainstream - young singles/couples and midage are more willing to pay more per packet of chips compared to their budget and premium counterparts.

### Customer Preferences Analysis
We have found quite a few interesting insights that we can dive deeper into. We might want to target customer segments that contribute the most to sales to retain them or further increase sales. 
Let’s look at Mainstream - young singles/couples. For instance, let’s find out if they tend to buy a particular brand of chips. 

**Brand affinity**: Measures the strength of a customer segment's preference for a specific brand compared to the general population or another group.
It shows how much more (or less) likely a particular group is to purchase a certain brand compared to others, which can reveal loyal or enthusiastic customer bases for specific products.

In this analysis, brand affinity is calculated by comparing the proportion of a specific brand's sales within a target segment (Mainstream Young Singles/Couples) against the proportion of that brand's sales among all other customers.If the target segment buys a particular brand significantly more than other segments, this indicates a high brand affinity.
(add result of affinity to brand)
- Mainstream young singles/couples are 23% more likely to purchase Tyrrells chips compared to the rest of the population.
- Mainstream youngsingles/couples are 56% less likely to purchase Burger compared to the rest of the population

I also tried to find out if our target segment( Mainstream Young Singles/Couples) tends to buy larger packs of chips.
(add result of affinity to pack)

- A preference for 270g packs, with Twisties being a popular brand in this size.
- Mainstream young singles/couples are 27% more likely to purchase a 270g pack of chips compared to the rest of the population
- And are 56% less likely to purchase a 220g pack of chips compared to the rest of the population.
  
**What brands sell this pack size (270g)**
- Twisties Cheese 270g
- Twisties Chicken 270g
- Twisties are the only brand offering 270g packs and so this may instead be reflecting a higher likelihood of purchasing Twisties.

### Conclusion and Recommendations
- In summary,the analysis shows that chip sales are primarily driven by three key shopper groups: Budget-conscious older families, Mainstream young singles/couples, and Mainstream retirees.
- The higher chip spending among Mainstream young singles/couples and retirees is largely due to the larger number of buyers in these segments.
- Additionally, Mainstream mid-age and young singles/couples are more inclined to pay a premium per packet, suggesting impulse-driven purchasing behavior.
- Notably, Mainstream young singles and couples are 23% more likely to buy Tyrrells chips compared to other population segments.
-  To boost category performance, the company could consider positioning Tyrrells and smaller chip packs in high-traffic, discretionary spaces where young singles and couples are more likely to shop. This strategy would increase visibility and encourage impulse purchases.
- By understanding the unique preferences of each segment, the company can better tailor its product placement and promotional efforts to boost overall category performance.
### Data Sources

