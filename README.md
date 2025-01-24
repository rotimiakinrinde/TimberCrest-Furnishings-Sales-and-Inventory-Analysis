# TimberCrest-Furnishings-Sales-and-Inventory-Analysis

### Overview

TimberCrest Furnishings operates across various U.S. cities, providing essential office supplies, furnishings, maintenance equipment, and more. The analysis aims to help the company ensure productivity and efficiency in public and private spaces by optimizing its sales performance, product inventory, and customer relationships.

### Objectives

The primary objectives of this analysis are to:

1. Understand sales performance across different product categories and customer segments.
2. Identify high-performing and underperforming products to optimize inventory management.
3. Analyze customer orders and geographic trends to improve sales strategies.
4. Provide actionable recommendations to enhance business profitability and operational efficiency.

## Key Insights

For this analysis, the Entity-Relationship Diagram (ERD) is critical for structuring and understanding the relationships between the three key tables Products, Orders, and PropertyInfo in the dataset. The ERD visually represents how the data entities (tables) connect. 

The Products table provides details about items sold, including categories, names, and prices. The Orders table links products to the properties that placed the orders, tracking quantities and dates. The PropertyInfo table provides geographic information about where each property is located.

However, the relationships (e.g., ProductID linking Products and Orders, and PropertyID linking Orders and PropertyInfo) allow us to merge and analyze these datasets comprehensively.
The ERD ensures the correct implementation of SQL joins to extract meaningful insights. The ERD ensures clear connections between tables to answer key business questions and reduces the complexity of understanding raw data by organizing it into meaningful relationships, enabling the analysis of trends, customer behaviour, and inventory performance.
![ERD ](https://github.com/user-attachments/assets/68e1cc6f-1e15-4e07-b1c9-4e5b4fd50b68)

The "Furnishings" category has the highest number of products (26), followed by "Public Areas" (21). "Office Supplies" has the lowest count (13), which indicates potential limitations in product diversity within this category.
A total of 10,096 products have been ordered, reflecting strong overall demand but requiring further breakdown to identify trends by category and location.
![SALES PERFORMANCE](https://github.com/user-attachments/assets/59948fca-77bd-47a5-a9d3-12574f272111)

The analysis indicates "Furnishings" category has the highest average price ($83.65), followed by "Public Areas" ($58.62), indicating premium pricing opportunities.
The top 5 most expensive products include: Bed (King): $300, Bed (Double): $250, Sofa: $215, Leaf Blower: $202
![Most Expensive products](https://github.com/user-attachments/assets/6820e350-76f3-44c0-847c-9639c2af9fa2)

This analysis also identifies Philadephia(551), Kansas City(545) and Chicago(539) with the highest orders and also indicates TimberCrest has a presence in diverse locations such as New York, Cincinnati, Portland, Seattle, and Las Vegas. This geographic diversity however requires tailored strategies for regional preferences.
Cities with the highest order quantities can be targeted for expanded inventory and focused marketing campaigns.
![Quantity ordered by region](https://github.com/user-attachments/assets/99015b37-64b2-4849-9ddd-edc2285e49d5)




### Recommendations

**Expand High-Performing Categories:**

* Focus on increasing product diversity within the "Furnishings" and "Public Areas" categories to capitalize on their higher average prices and profitability.

**Enhance Office Supplies Offering:**

* Introduce new products in the "Office Supplies" category to address its limited selection and potentially boost sales.

**Target Regional Strategies:**

* Customize marketing campaigns and inventory levels for top-performing cities and states to align with local preferences and demand.

**Promote Premium Products:**

* Highlight high-value products like "Bed (King)" and "Sofa" in marketing efforts to drive profitability.

**Optimize Inventory Management:**

* Regularly review sales data to identify underperforming products for potential phase-out or promotional discounts.

**Leverage Year-over-Year Trends:**

* Use historical data to forecast demand, plan inventory, and design seasonal promotions to capture peak periods.


### Conclusion

This analysis highlights TimberCrest Furnishings’ strengths in premium product categories like "Furnishings" and geographic diversity. By leveraging data-driven insights, the company can refine its product offerings, tailor strategies to high-performing regions, and enhance profitability. Continuous monitoring and iterative improvements will ensure sustained growth and operational excellence.
