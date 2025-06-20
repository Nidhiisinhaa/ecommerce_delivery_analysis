E-commerce Delivery & Returns Analysis:

This project explores a retail dataset containing product orders, shipping dates, delivery timelines, and return information. The goal is to identify patterns in delays and returns using real-world-style messy data.

What's Inside:
-Cleaned and structured the dataset by:
  -Removing duplicates
  -Converting date columns to datetime
  -Handling missing values
-Engineered new columns like:
  -Delivery_Delay (Delivery Date - Ship Date)
  -Order_to_Ship (Ship Date - Order Date)
-Performed exploratory analysis:
  -Average delivery delay by region
  -Return counts by product category
  -Delay patterns by shipping mode
-Visualized findings using matplotlib

Tools Used:
-Python
-Pandas
-Matplotlib
-Jupyter Notebook

Key Insights:
Certain regions consistently showed higher delivery delays
Some product categories had more returns
Standard shipping often caused more delay than other modes

