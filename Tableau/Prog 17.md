---
tags:
  - tableau
  - program
---
>[!question] Using the Sample-superstore data source, find the variation of Sales for each Sub Category of products and make a waterfall chart

1. Drag the Dimension Sub-Category to the Columns shelf and the Measure Sales to the Rows shelf. Sort the data in an ascending order of sales value. For this, use the sort option appearing in the middle of the vertical axis when you hover the mouse over it. 
2. Next, right-click on the SUM (Sales) value and select the running total from the table calculation option. Change the chart type to Gantt Bar. The following chart appears 
3. Create a calculated field named -sales and mention the –(sales)formula for its value. 
4. Drag the newly created calculated field (-sales) to the size shelf under Marks Card. The chart above now changes to produce the following chart which is a Waterfall chart

![[17_waterfall.png]]