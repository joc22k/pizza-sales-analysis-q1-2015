#  Pizza Sales Analysis — Q1 2015
Python and Pandas analysis of pizza sales, revenue trends, and product performance in Q1 2015. 

**A data analytics project exploring sales performance, product preferences, revenue trends, and customer purchasing patterns during the first quarter of 2015.**

## Project Overview

This project analyzes the sales performance of a pizza chain from January to March 2015. Using Python and Pandas, I explored sales transactions to identify revenue trends, evaluate product performance, compare monthly results, and investigate purchasing patterns across different days.

The goal was to transform raw sales data into actionable business insights that could support inventory planning, product promotion, and sales strategy.

## Business Questions

This analysis focuses on the following questions:

- How did revenue and pizza sales change from January to March?
- Which pizzas sold the highest quantities each month?
- Which products generated the most revenue?
- How did product performance vary across the three months?
- What proportion of monthly revenue came from the top five and top ten pizzas?
- Which days recorded the strongest sales performance?
- What patterns could help inform future sales and marketing decisions?

## Tools and Technologies

- **Python** — data analysis and calculations
- **Pandas** — data cleaning, merging, grouping, and aggregation
- **Jupyter Notebook** — analysis workflow and documentation
- **Matplotlib / Seaborn** — visualizations, if used in the project
- **Power BI** — interactive reporting, if used in the project

## Dataset and Preparation

The analysis uses pizza order details, pizza product information, and order dates and times.

The preparation process involved:

1. Loading the source datasets into Pandas.
2. Checking and standardizing relevant columns and data types.
3. Merging order details with product information and order dates.
4. Converting order dates into a datetime format.
5. Calculating revenue using the quantity sold and unit price.
6. Filtering records to include the first quarter of 2015.
7. Aggregating sales by month, pizza type, and date.

**Revenue calculation:**

`Revenue = Quantity Sold × Unit Price`

## Analysis and Findings

### 1. Monthly Sales Performance

#### January

January generated approximately **$69,000 in revenue**, according to the initial analysis. Pepperoni was the leading pizza by quantity sold, with more than 4,000 units recorded.

The first week also featured a particularly strong sales day. This provided an opportunity to investigate daily sales fluctuations and identify periods of high demand.

#### February

February generated approximately **$65,000 in revenue**. Pepperoni remained a leading product by quantity sold, suggesting that it continued to attract customers.

Based on the rounded revenue figures of $69,000 and $65,000, revenue declined by approximately **5.8%** from January. Further analysis of daily and weekly performance can help determine whether the decline was broad-based or concentrated in particular periods.

#### March

March showed a change in product performance, with Barbecue Chicken (`bbq_ckn`) emerging as a leading product in the analysis. The dataset also recorded 4,621 units sold for the metric initially examined.

This result highlights the importance of monitoring product preferences over time rather than assuming that the best-performing product will remain unchanged.

### 2. Product Performance: Barbecue Chicken

Barbecue Chicken was among the strongest-performing products during the quarter.

The initial analysis indicated that it contributed approximately 5.4% of January revenue and 5.2% of February revenue. In March, its revenue contribution increased to approximately 5.8–5.9%, depending on the calculation used.

These figures suggest that Barbecue Chicken was an important contributor to overall sales. Comparing its quantity sold, revenue, average selling price, and order frequency provides a more complete picture of its performance.

**Key business insight:** The product with the highest quantity sold does not necessarily generate the highest revenue. Product prices, order quantities, and the mix of products purchased all influence revenue performance.

### 3. Monthly Product Breakdown

#### January

The five leading products reportedly contributed 24.2% of monthly revenue, while the top ten contributed approximately 40%.

This indicates that a relatively small selection of products accounted for a substantial share of sales. Such findings can inform inventory management and product promotion.

#### February

The top ten products reportedly contributed approximately 44% of monthly revenue, compared with 40% in January.

Although total revenue was lower, the larger revenue share attributed to the top ten products suggests that sales may have been more concentrated among leading products. This should be confirmed by checking the product-level revenue calculations.

#### March

The top ten products reportedly contributed approximately 41% of monthly revenue.

This indicates that the leading products continued to account for a substantial portion of monthly sales, although the concentration was lower than the reported February figure.

Together, these comparisons demonstrate why businesses should examine both total revenue and the distribution of revenue across products.

### 4. Daily Sales Performance

The initial analysis identified strong sales activity during parts of the first and last ten days of the months.

This observation provides a basis for further investigation into daily revenue, quantities sold, and weekly patterns. However, the concentration of high-sales days should be verified across all three months before drawing a general conclusion.

Potential explanations, such as salary payment cycles, promotional campaigns, weekends, and public holidays, would require additional data before they could be established as causes.

## Recommendations

Based on the patterns identified, the business could consider:

- **Inventory planning:** Monitor leading products to reduce the risk of stock shortages.
- **Product promotion:** Investigate why Barbecue Chicken performed strongly in March and test targeted promotions where appropriate.
- **Revenue optimization:** Evaluate both sales volume and revenue when prioritizing products.
- **Monthly performance tracking:** Compare revenue, orders, and units sold to identify changes in demand.
- **Sales timing:** Examine high-performing dates and weekdays to guide staffing, inventory, and marketing decisions.

These are recommendations for further investigation and testing, not proof that a particular intervention will increase sales.

## Conclusion

This project demonstrates how transaction-level data can be transformed into meaningful business insights. By analyzing monthly performance, product-level revenue, and daily sales patterns, I explored how sales outcomes varied throughout Q1 2015.

The analysis also highlights the value of using multiple performance measures. Quantity sold, revenue, and revenue contribution provide different perspectives on product performance and can support more informed business decisions.

## Skills Demonstrated

- Data cleaning and preparation
- Data merging and transformation
- Exploratory data analysis (EDA)
- Grouping and aggregation with Pandas
- Revenue and sales calculations
- Trend and product performance analysis
- Business interpretation and recommendations
- Analytical reporting and documentation

## Project Structure

```text
pizza-sales-analysis-q1-2015/
├── README.md
├── notebooks/
│   └── pizza_sales_analysis.ipynb
├── data/
│   ├── orders.csv
│   ├── order_details.csv
│   └── pizzas.csv
└── reports/
    └── charts/
```


## Reproducing the Analysis

1. Clone or download this repository.
2. Install Python and the required libraries.
3. Open the Jupyter Notebook.
4. Ensure the dataset paths match the files on your computer.
5. Run the notebook cells in order to reproduce the analysis.

Example installation:

```bash
pip install pandas jupyter matplotlib seaborn
```

## Project Status

**Completed:** Initial Q1 sales analysis and business interpretation.

**Potential next steps:** Validate all reported figures, improve visualizations, and develop an interactive Power BI dashboard.
