# Sales Analysis with Excel
## Project overview
* An electronics store needs to increase its profits
* A KPI is found that will allow to increase profits at the lowest cost.
* Sales were evaluated by product, city, time and over time.
* This analysis was done on a database with 180,000 values using Excel only.

## Objective:
### Questions that will drive the analysis
* Which products of all the stores generates the highest and lowest profits?
* Which months will generate the highest profits and on which dates and states?
* What is the best time to sell our products?

## Data cleaning and data preparation
The data shows the sales of an electronics store, you can see the raw data [HERE](https://github.com/victort9/Excel_Analysis_Project/tree/main/Files). As you can see in the image below, the format of the data was not appropriate for the analysis, so it had to be cleaned and prepared.

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Raw_data.png)

The activities performed were the following:

* Eliminate duplicates and cells that did not correspond to the data.
* Eliminate or correct missing values
* Adjust the dates because they did not have the proper format.
* Create the time, city and state columns for the analysis.
* The dataset consists of a single table with 13 columns and almost 3.4 million rows.

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Cleaned_data.png)

## Data Analysis:
The analysis was done using Excel pivot tables and visualizations considering the target questions.

* Which product of all the stores generates the highest and lowest profits: For this, the products were analyzed with respect to sales.

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/top_products_profit.png)
![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Bottom_5_num_sales.png)

* Which months will generate the highest profits and on which dates and state? The sales analysis was made over time

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Sales_by_month.png)

* What is the best time to sell our products? The time and days of the week were used to evaluate the sales performance in a week.

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Sales_by_hour.png)

## Visualizations
Finally we obtained a dashboard with 2 sheets showing the sales in a general way and the other one showing the performance of these at different times of the day and weeks. You can see the dashboards below and you can access the document by clicking [HERE](https://github.com/victort9/Excel_Analysis_Project/tree/main/Files).

![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Performance_overview.png)
![](https://github.com/victort9/Excel_Analysis_Project/blob/main/Images/Sales_overview.png)

PS. Since the file "Sales_Data_2019_Report" is larger than 25 MB I have decided to separate the sheet with the final data to another file called "Sales_Data_2019_Final_Data".

## Conclusions
* Despite being the least sold product, the MacBook Pro Laptop remains the best selling product every month. The product with the least number of sales is the LG Dryer.
* The best times to sell are at 12:00 and 19:00 on Tuesdays, October and December are the best selling months.
* Sales in California were much higher than in the other states, concentrating marketing efforts here would generate higher profits but it is necessary to analyze the competition and market saturation for a better conclusion.
* It is advisable to focus marketing efforts on the MacBook Pro as slightly increasing sales in this product could considerably increase profits. It is advisable to find another product to sell that can generate more sales than the LG Dryer.
