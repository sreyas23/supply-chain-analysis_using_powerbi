# Supply Chain Analysis Using PowerBI

## Project Description  
I carried out this analysis in a Jupyter Notebook (inside VS Code) using pandas to explore a fashion & beauty startup’s supply chain data. My goal was to clean and structure the data, then answer a series of business questions everything from sales trends to defect rates to pricing impact using groupby, aggregation, and visualizations to uncover actionable insights.

## Dataset  
The dataset tracks every stage of our supply chain:  
- **Sourcing & Manufacturing**: product lines, production dates  
- **Inventory**: stock levels, lead times  
- **Shipping**: transport modes, routes, costs, defect counts  
- **Sales**: units sold, revenue, customer demographics  
- **Quality**: inspection results  

I downloaded it from StatSo’s Supply Chain Case Study:   https://statso.io/supply-chain-analysis-case-study/

## Tools & Environment  
- **Language & Libraries**: Python 3.x, pandas, NumPy, matplotlib  
- **IDE**: VS Code with Jupyter extension  
- **Output**: Jupyter Notebook (`.ipynb`) with inline charts

## Data Preprocessing  
1. **Import CSV** into a pandas DataFrame  
2. **Inspect** with `.head()` and `.info()` to understand structure  
3. **Drop duplicates** to remove exact row repeats  
4. **Fill missing values** in numeric columns with the column mean  

After cleaning, the data was ready for exploration and feature creation.

## Analysis Performed  
- **Descriptive Statistics**: summary of distribution, counts, means  
- **Sales Analysis**: unit sales and revenue by product type and customer demographic  
- **Inventory Analysis**: average lead time and stock levels to assess fulfillment capability  
- **Defect Rate Analysis**: defect percentages by product and by transport mode  
- **Quality Inspection**: pass/fail counts across product lines  
- **Transportation & Route Optimization**: average shipping cost per route, cost-efficiency comparison  
- **Revenue Analysis**: total revenue by product and scenario testing of a 10% price increase  
- **Trend Analysis**: examining seasonality or periodic patterns in sales over time

## Business Questions Answered  
- What’s the sales breakdown by product line and customer segment?  
- Can the company meet demand on time (lead times) and avoid stock-outs?  
- Which products have the highest defect rates, and which transport modes contribute most?  
- How do inspection pass rates compare across cosmetics, skincare, and haircare?  
- Which shipping routes deliver the best cost efficiency?  
- What share of total revenue does each product type generate?  
- How much additional revenue could a 10% price increase bring?

## Power BI Insights

![powerbi_insights report](https://github.com/sreyas23/supply-chain-analysis_using_powerbi/blob/6a787714f9686d147b7785189c282864baea0719/PowerBI_Report_sreya.png)


## Key Insights  
- **Top Sellers**: Cosmetics lead in units sold; Skincare drives the biggest revenue share  
- **Inventory Health**: Some haircare and skincare lines show longer lead times and lower stock buffers  
- **Quality Risks**: Haircare products have the highest defect rates—time to review handling or packaging  
- **Shipping Efficiency**: Route A is the most cost-effective on average—consider rerouting more volume through it  
- **Pricing Impact**: A modest 10% price hike could yield a sizable lift in overall revenue

## Next Steps  
- Build demand forecasting models to anticipate inventory needs  
- Run A/B tests to validate price elasticity assumptions  
- Drill down on defect root causes (e.g., packaging, transport conditions)  
- Automate the analysis pipeline for ongoing supply chain monitoring  
