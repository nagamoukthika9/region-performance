# Region Performance Analysis – Superstore

Compare sales and profit across regions of the Superstore dataset to see which regions drive revenue and which actually drive profit.

## Objective

Practice grouping and comparison: summarize sales and profit by region, rank the regions, and visualize the result.

## Dataset

- **Source:** Sample – Superstore (`Sample_-_Superstore.csv`)
- **Size:** 9,994 order lines
- **Columns used:** `Region`, `Sales`, `Profit`

## Tools

- Microsoft Excel (SUMIFS, RANK, charts)

## Approach

1. Loaded the Superstore orders into the `Data` sheet.
2. Built a region summary with `SUMIFS` for total sales and total profit.
3. Calculated profit margin (`Profit / Sales`) and each region's share of total sales.
4. Ranked regions by sales and by profit using `RANK`.
5. Charted sales and profit side by side in a clustered bar chart.



Key Insights

- West leads in both sales and profit, with the highest margin (14.9%).
- East is a strong second on both measures (13.5% margin).
- Central is third in sales but last in profit; its 7.9% margin is the lowest, so discounting and costs there are worth investigating.
- South has the lowest sales but a better margin (11.9%) than Central, so it ranks third in profit.

 Why compare profit with sales?

Sales shows volume; profit shows whether that volume is worth having. Ranking by sales alone would overrate Central.

How would I rank the regions?

By profit, checking margin alongside it: West > East > South > Central.

 Files

Region_Performance.xlsx – region summary, bar chart, insights, and source data
Sample_-_Superstore.csv – raw dataset

