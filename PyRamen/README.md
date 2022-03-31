# Week 2 Homework - PyRamen
This consists of the main.ipynb Jupypter notebook. The script reads [menu_data.csv](Data/menu_data.csv) consisting of menu items and and the corresponding sales data [sales_data.csv](Data/sales_data.csv) and create a report with required metrics.

This script will parse through two csv files one which will have the menu details such as item name, cost and price and sales files which will have the sale of each item

After parsing the files, the script will create a report dictionary with each menu item being the key
and calculating the metrics such as total sales, revenue, cost base and profit. 

After calculating the metrics, the content of the report dictionary will be printed on the screen and also written to a text file.