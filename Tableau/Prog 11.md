---
tags:
  - tableau
  - program
---
>[!question] Using the Sample-superstore data source, find the top 10 Sub-Category of products for the category called Furniture \[Context filtering\]

1. Drag the dimension Sub-Category to the Rows shelf and the measure Sales to the Columns Shelf. Choose the horizontal bar chart as the chart type. Drag the dimension Sub-Category again to the Filters shelf. 
2. Right-click on the field Sub-Category in the filter shelf and go the fourth tab named Top. Choose the option by field. From the next drop-down, choose the option Top 10 by Sales Sum 
3. Drag the dimension Category to the filter shelf. Right-click to edit and under the general tab choose Furniture from the list. As you can see the result shows three subcategory of products. 
4. Right-click the Category: Furniture filter and select the option Add to Context. This produces the final result, which shows the subcategory of products from the category Furniture which are among the top 10 subcategories across all the products
![[11_subcatfurniture.png]]