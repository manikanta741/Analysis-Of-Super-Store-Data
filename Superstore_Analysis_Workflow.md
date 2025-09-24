Project Overview

This project analyzes Superstore sales data using Python to generate actionable business insights. Below is a concise, sectioned explanation of the workflow and functionalities.

1. Data Section

This section explains how the dataset is handled.

1.1. How is the dataset loaded?
Answer: The dataset is loaded using pandas.read_csv() and previewed to check its structure, size, and columns.

1.2. How is missing or duplicate data handled?
Answer: Missing values are identified using isnull() and duplicates are removed using drop_duplicates().

1.3. How are date columns processed?
Answer: Order Date and Ship Date are converted to datetime format to enable time-based analysis.

1.4. What feature engineering is performed?
Answer: Additional columns like Profit_Margin and Sales_per_Customer are created, and year/month features are extracted from Order Date.

2. Exploratory Data Analysis (EDA)

This section explains how sales, customers, and products are analyzed.

2.1. How is sales analyzed by category?
Answer: Total sales are aggregated by category and visualized with a bar chart.

2.2. How are monthly sales trends analyzed?
Answer: Sales are grouped by month and plotted to observe trends and seasonality.

2.3. How are top products identified?
Answer: Products are ranked by sales and profit to identify top-selling and top-profitable items.

2.4. How is sales share by segment analyzed?
Answer: Customer segments’ contributions to sales are visualized using a pie chart.

3. Customer Analysis

This section explores customer behavior.

3.1. How are purchasing patterns analyzed?
Answer: Average order values are calculated per segment and visualized.

3.2. How is the relationship between sales and profit analyzed?
Answer: A scatter plot is created to show correlation between sales and profit, colored by category.

4. Product Performance Analysis

This section focuses on profitability and inventory.

4.1. How is profitability analyzed?
Answer: Total profit is calculated by category and visualized using bar charts.

4.2. How is profit distribution analyzed?
Answer: Histograms show distribution of profit across all products.

4.3. How are fast- and slow-moving products identified?
Answer: Products in the top 20% of sales are fast movers; bottom 20% are slow movers.

5. Sales Forecasting

This section explains predictive analysis.

5.1. How is forecasting performed?
Answer: Monthly sales are modeled using Linear Regression.

5.2. How is accuracy measured?
Answer: Mean Absolute Percentage Error (MAPE) is used to evaluate prediction accuracy.

5.3. How are predictions visualized?
Answer: Actual vs predicted sales are plotted to observe forecast performance.

6. Correlation Analysis

This section examines relationships between metrics.

6.1. Which metrics are analyzed?
Answer: Discount, quantity, profit, and sales.

6.2. How are relationships visualized?
Answer: A correlation heatmap is created using Seaborn.

7. Insights and Decision-Making

This section summarizes actionable outcomes.

Identify high-performing products and categories.

Understand customer purchasing behavior.

Optimize inventory based on fast- and slow-moving products.

Forecast future sales for better planning.

Leverage correlations to improve pricing, discounts, and profitability.
