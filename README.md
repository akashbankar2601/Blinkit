# “Blinkit Analytics: Mapping Growth and Market Potential”

## Project Overview
This project focuses on analyzing the Blinkit dataset to enhance the company's operations and customer engagement through data-driven insights. The analysis contains information on various products, outlet establishments, and customer interactions.

### Dataset
https://docs.google.com/spreadsheets/d/1tdF_beuexr4n46cuZY8P-b8JCCYN-SNZ/edit?usp=drive_link


## import libraries
import numpy as np
import math
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd

## Requirements
numpy==1.23.1
pandas==1.4.3
matplotlib>=3.3.0
seaborn>=0.11.0
## Key Insights
### 1. Best-Selling Products and Categories
- Group the Data: Use Pandas to group the dataset by product and category.
- Aggregate Sales: Sum the sales quantities or revenue for each group. 
- Sort the Results: Sort the aggregated data in descending order to identify the   top-selling products and categories.

## 2. Outlet Establishment by Year
- 2018 saw the highest number of new outlet establishments, with a peak percentage of 17.17% of the total outlets.
- The distribution of outlet establishments across other years shows relatively similar rates, with the lowest in 2011 at 6.51%.
- reason for the high number of new outlets in 2018 could be the completion of previous infrastructure or technology upgrades, enabling Blinkit to scale its operations more effectively. In 2011, the company might have been in the earlier stages of these upgrades or dealing with market uncertainties, leading to slower expansion.

## 3. Average Product Rating
-The horizontal line plot highlights the average product rating, providing an easy visual comparison with a scatter point that marks the average rating value.

## 4. Store Types Distribution
- The analysis revealed that "Supermarket Type1" is the most prevalent store type in the dataset, accounting for approximately 65.43% of the total.
- Other types include "Grocery Store" at 12.71%, "Supermarket Type3" at 10.97%, and "Supermarket Type2" at 10.89%.(Supermarket Type1, Type2, and Type3 likely represent different formats or scales of supermarkets. Type1 could be smaller, neighborhood-focused stores offering essential items. Type2 might be mid-sized supermarkets with a broader range of products. Type3 could be large, hypermarket-style outlets with extensive product varieties and additional services like pharmacy and electronics.)

## 5. Item Fat Content Distribution
- The dataset shows a dominance of "Low Fat" items at 59.71%, followed by "Regular" items at 33.90%. Minor variations such as "LF," "reg," and "low fat" indicate inconsistencies in labeling but confirm that low-fat items are more prevalent.
  
## 6. Outlet Location Tier Distribution
- Outlets are mostly located in Tier 3 areas (39.31%), followed by Tier 2 at 32.68%, and Tier 1 at 28.02%.The reasons is Cost Efficiency, Market Penetration, Expanding Customer Base (reason of why tier 3 more than tier 1 is Operating in Tier 3 areas generally involves lower real estate and rental costs, making it more feasible to open multiple outlets within budget constraints.)

## Methodology
- The project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology, ensuring a structured and comprehensive analysis process.

  
## Conclusion
- The analysis of Blinkit's data reveals key insights that can significantly enhance operational efficiency and customer engagement. By focusing on the most successful product categories, Blinkit can optimize its inventory and marketing efforts to boost sales. Understanding the distribution patterns of outlets allows for strategic expansion and resource allocation, ensuring that demand is met more effectively. To maintain a high level of customer satisfaction, it is crucial to standardize and improve product labeling across all locations.

## Acknowledgment
-I would like to acknowledge the support and resources provided by the Blinkit team, whose dataset was essential for this analysis, and express gratitude to all who contributed insights and feedback throughout the project.