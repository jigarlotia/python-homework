# Week 2 Homework - PyBank
This consists the main.ipynb Jupypter notebook. The script reads [budget_data.csv](Data/budget_data.csv) which is composed of two columns, Date and Profit/Losses. The script then calculates:

- The total number of months included in the dataset.
- The net total amount of Profit/Losses over the entire period
- The average of the changes in Profit/Losses over the entire period.
- The greatest increase in profits (date and amount) over the entire period
- The greatest decrease in losses (date and amount) over the entire period.

The output would be generated as below:
  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```