---
tags:
  - powerbi
date: 2023-11-08
---


>[!question] 
>- Import a excel worksheet in PowerBI
>- Create a multipage report which contains at least 4 charts for the imported dataset.
>- Delete unwanted/ unused columns in the dataset.
>- Create a new column in PowerBI using any of the two existing fields available in the dataset.
## A Simple Multipage Report
Make use of ask a question about your data by double left clicking the dashboard.
![[pbi_lab1.png]]


## Create a column
Choose the table view in the side
- Go To Table View
- Choose the new column option which shows equation thing just like an excel sheet.
- Change `Column` to a preferred name we'll go with `Profit_Sales_Ratio`
- We use some formula `Profit_Sales_Ratio = ([Profit]*100)/[Sales]` and hit enter to make a new column

## Delete a column
Right Click the newly created column and click delete.
