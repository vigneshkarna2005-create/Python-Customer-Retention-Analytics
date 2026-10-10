# Sales and Profit Analysis Using Python

Exploratory data analysis of e-commerce sales data using Python, Pandas and Matplotlib to understand sales and profit by category, customer segment and region.

## Business Problem
Which product categories, customer segments and regions drive the most sales and profit?

## Dataset
- File: `CLEANED DATASET 2.csv` (cleaned e-commerce sales data)
- Columns used: Category, Customer_Segment, Region, Sales, Profit
- Source: [dataset name / self-created: write what is true]

## Analysis Steps
1. Loaded the dataset with Pandas
2. Checked the shape, column names, data types, missing values and duplicate rows
3. Generated a statistical summary
4. Calculated total sales, total profit and average sales
5. Grouped sales and profit by category, customer segment and region
6. Visualized the results with Matplotlib bar charts

## Key Metrics
- Total Sales: about 28.17M
- Total Profit: about 5.20M
- Profit Margin: about 18.5%

## Visualizations


![Sales by Category](Sales%20by%20Category.png)




![Profit by Category](Profit%20by%20Category.png)




![Sales by Customer Segment](Sales%20by%20Customer%20Segment.png)




![Sales by Region](Sales%20by%20Region.png)




![Profit by Region](Profit%20by%20Region.png)



## Key Insights
1. The business earned about 28.17M in sales and 5.20M in profit, a profit margin of about 18.5%.
2. Electronics is the largest category in both sales and profit, while Bags and Stationery contribute very little.
3. [Add the top customer segment from your Sales by Customer Segment chart]
4. [Add the top region from your Sales by Region and Profit by Region charts]

## Recommendations
- Focus marketing and stock on Electronics, since it drives most of the sales and profit
- Review pricing and promotion for low-performing categories such as Bags and Stationery
- Target the top customer segment and region with offers

## Files
- `churn_analysis.py`: analysis script
- `CLEANED DATASET 2.csv`: cleaned dataset
- `requirements.txt`: required libraries
- PNG files: chart outputs

## How to Run
pip install -r requirements.txt
python churn_analysis.py

## Tools
Python, Pandas, NumPy, Matplotlib

## Contact
Vignesh K | vigneshkarna2005@gmail.com | [LinkedIn](https://www.linkedin.com/in/vignesh-k-a46146368)
