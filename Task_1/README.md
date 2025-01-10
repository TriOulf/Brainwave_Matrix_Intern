# Superstore Sales Data Analysis

## Requirements

- Python 3.x
- pandas
- plotly


## 1. Data Preprocessing:
**Loaded the dataset:** You imported the dataset using pd.read_excel.
**Checked for missing values:** There were no missing values.
**Converted data types:** You ensured that the 'Order Date' and 'Ship Date' columns were in datetime format.
**Created new columns for:**
Order Month (Month of the order)
Month (Month name)
Order Year (Year of the order)
Order Day of Week (Day of the week for the order)
## 2. Exploratory Data Analysis (EDA):
**Descriptive Statistics:** You summarized the data using .describe(), which provided insights like the mean, standard deviation, and range of columns like sales, profit, and quantity.
**Check for Null Values:** No missing data was found.
## 3. Visualizations:
**Monthly Profit Trends:** You created a line chart to visualize profit trends by month across different years.
**Monthly Sales and Profit:**
Line charts were used to show total sales and total profit over time.
**Sales, Profit, and Loss by Category/Sub-Category:**
**Treemap:** Visualized sales, profit, and loss across product categories and sub-categories.
**Bar Charts:** Analyzed sales and profit by category and sub-category.
**Profit Analysis:**
Pie charts for profit by category and sub-category.
**Geographical Analysis:**
Sales, Profit, and Loss by Country, State, City, and Region:
Grouped data by these dimensions and visualized sales, profit, and losses.
**Sales Distribution by Region:** Pie chart to show sales distribution across regions.
**Segment-wise Sales and Profit:** Bar chart for sales and profit by customer segment.
**Top-Selling and Low-Performing Products:**
Bar charts for top-selling products based on sales and low-performing products based on profit.
**Time-Based Analysis:**
**Monthly Sales and Profit:** This section visualizes the total sales and profit for each month. a line plot displaying monthly sales and profit trends.
**Quarterly Trends:** This section extracts quarterly data and visualizes sales trends by quarter. a bar chart showing the total sales for each quarter.
**Discount Impact on Sales and Profit:** This section examines the effect of discounts on sales and profit. a scatter plot that shows the relationship between discount percentage and sales. scatter plot displaying how discounts affect profit across different product categories.
**Product-Level Performance:** This section analyzes the relationship between sales, profit, and quantity at the product level. scatter plot illustrating sales, profit, and quantity for each product, with color indicating sub-category.
## Conclusion:
This analysis provides valuable insights into sales trends, the impact of discounts, and product performance, helping businesses make informed decisions to improve profitability.
