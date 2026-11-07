# India Retail Sales & Customer Analytics

## Project objective
Analyze 10,000 synthetic retail order records to understand revenue, profitability, customer behaviour, product-category performance, regional performance, sales channels, discount effectiveness, and product returns. Convert the findings into practical business recommendations.

## Dataset
`india_retail_sales_10000.csv` contains 10,000 transaction-level records for calendar year 2025. It is synthetic, created for learning and portfolio use; it is not real company data.

### Key columns
- Order_ID, Order_Date: transaction identifier and date
- Customer_ID, Age, Gender: customer attributes
- State, City: geographic attributes
- Category, Sub_Category: product hierarchy
- Quantity, Unit_Price_INR, Discount_Pct: order and pricing details
- Sales_INR, Cost_INR, Profit_INR, Profit_Margin_Pct: financial measures
- Sales_Channel, Payment_Method, Returned, Order_Month: channel, payment, return and time dimensions

## Suggested analysis questions
1. Which months generate the most revenue?
2. Which categories contribute most to revenue and profit?
3. Which states and cities are the strongest markets?
4. Which sales channel contributes the most revenue?
5. Are larger discounts associated with lower order profit?
6. Which categories have the highest return rates?
7. What customer age groups contribute most orders?

## Visuals included in Python script
Monthly revenue line chart; category revenue and profit bar charts; state revenue bar chart; channel revenue pie chart; discount-versus-profit scatter plot; return-rate bar chart; age distribution histogram.


## Run the project
```bash
pip install pandas matplotlib seaborn
python retail_sales_analysis.py
```
Keep both files in the same folder.

## Important note
The dataset includes deliberately designed patterns for educational analysis. Treat discovered patterns as findings within this synthetic dataset, not as claims about the Indian retail market.
