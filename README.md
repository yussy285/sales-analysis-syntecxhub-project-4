# sales-analysis-syntecxhub-project-4
# Sales Analysis Project

**Syntecxhub Data Analysis Internship, Project 4**

An end-to-end analysis of a retail sales dataset: cleaning the data, calculating business KPIs, finding trends and seasonality, and turning the results into recommendations.

## Objective

Answer key business questions about a retail store: which products sell best, which regions perform strongest, and when sales peak.

## Dataset

Superstore Sales dataset from Kaggle: [https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting]

About 9,800 order lines with 18 columns, including order date, region, category, product name and sales. The dataset is not included in this repository. Download `train.csv` from Kaggle and place it next to the notebook to run it.

## What I Did

1. **Cleaned the data:** converted day/month/year dates to proper date types, checked for missing values, removed duplicates.
2. **Calculated KPIs:** total revenue, number of orders, average order value, revenue by region, top 10 products.
3. **Analyzed trends and seasonality:** monthly revenue over time and revenue by calendar month.
4. **Visualized the results:** line and bar charts combined into a one-page PDF summary.
5. **Wrote recommendations** based on the findings.

## Key Findings

- **Total revenue:** $2.26M from 4,922 orders
- **Average order value:** $459.48
- **Seasonality:** September, November and December generate 43% of annual revenue, while January and February are the weakest months (about 7% combined)
- **Regions:** West (31%) and East (30%) lead, Central follows at 22%, and South is lowest at 17%
- **Products:** Office equipment dominates the top 10. The Canon imageCLASS 2200 copier is the best seller at $61.6K, 2.2x the runner-up. The top 10 products make up only about 11% of revenue, so sales are well diversified.

## Recommendations

1. Prepare inventory and launch campaigns early for the Sep to Dec peak.
2. Use promotions and bundles to lift slow months such as January and February.
3. Keep investing in West and East, and investigate why South underperforms (fewer customers or smaller orders?).
4. Keep top office equipment well stocked and cross-sell related items like binding supplies.

## Limitations

The dataset contains sales only, with no cost or profit data, so "top products" means highest revenue, not highest profit.

## Tools

Python, pandas, matplotlib, Google Colab

## Author

**Yusrah Sani-Giwa**, Second-year Computer Science student
