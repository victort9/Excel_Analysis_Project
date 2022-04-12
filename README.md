# Sales Analysis with Excel
## Project overview
* An electronics store needs to increase its profits
* A KPI is found that will allow to increase profits at the lowest cost.
* Sales were evaluated by product, city, time and over time.
* This analysis was done on a database with 180,000 values using Excel only.

## Objective:
### Questions that will drive the analysis
The goal is to find what can we do to motivate the users to change from casual subscription to annual subscription.

## Data transformation and data preparation
These datasets contain Cyclistic's historical trip data in 2020. The data has been made available by Motivate Inc. and was downloaded in a csv file and transformed using SQLite to use them in Tableau.

I've put my focus on the 2020 period as it's the most recent period where we have the data from a whole year, and so we can compare it with future years.

The dataset consists of a single table with 13 columns and almost 3.4 million rows.

You can see all the SQL queries [HERE](https://github.com/victort9/Victor-Projects/tree/main/Query):

![](images/Query.PNG)

## Data model:
You can see in this image the data model used in Tableau after the data was extracted.

![Data model](images/Data model.png)

## Visualizations
The final product is a presentation in Google Presentation of my findings.

You can see the result here [HERE](https://docs.google.com/presentation/d/1-W0WErICYOC2aFaU2lhP7XbpT2kkeuYIDDBILigH88o/edit#slide=id.p)

## Conclusions
* The best month to focus the campaings are June and September.
* The Casual users have leisure, and tourism rides mostly on weekends. The Annual/Member users have commute rides, during all week, so their behavior is different.
* The Casual users are more likely to take the electric bike rather than the Annual/Member users.
* I would suggest that in order to convert the casual to the annual users it would be interesting to focus the messages on people that uses the bike in a more leisure or commute way, depending on whether you want casual or annual users. Maybe offer some kind of promotion related to weekends and/or electric bikes if you aim for casual users.
