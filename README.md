# Heroes-of-Py
Data Analysis on a fantasy video game using Pandas.



# Objective
The objective of this project is to emulate the tasks of a Lead Analyst on an independent gaming company.

The data provided contains demographic and purchasing information about the fictional game Heroes of Pymoli. Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience.

A Data Analytics report has to be created to break down the game's purchasing data into meaningful insights.

Final report should include each of the following:

Player Count

![image](https://user-images.githubusercontent.com/54809591/80610072-e551c680-8a06-11ea-999e-490e9b5cc91c.png)

Purchasing Analysis (Total)

![image](https://user-images.githubusercontent.com/54809591/80610244-1d590980-8a07-11ea-99e4-da94d9afa49f.png)

Number of Unique Items

Average Purchase Price

Total Number of Purchases

Total Revenue

Gender Demographics

![image](https://user-images.githubusercontent.com/54809591/80611027-141c6c80-8a08-11ea-85ce-77938613de4c.png)

Percentage and Count of Male Players

Percentage and Count of Female Players

Percentage and Count of Other / Non-Disclosed

Purchasing Analysis (Gender)

The below each broken by gender


Purchase Count

Average Purchase Price

Total Purchase Value

Normalized Totals

Purchasing Analysis (Age)

The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)

Purchase Count

Average Purchase Price

Total Purchase Value

Normalized Totals

Top Spenders

Identify the the top 5 spenders in the game by total purchase value, then list (in a table):

SN

Purchase Count

Average Purchase Price

Total Purchase Value

Most Popular Items

Identify the 5 most popular items by purchase count, then list (in a table):

Item ID

Item Name

Purchase Count

Item Price

Total Purchase Value

Most Profitable Items

Identify the 5 most profitable items by total purchase value, then list (in a table):

Item ID

Item Name

Purchase Count

Item Price

Total Purchase Value

# Data Source

A JSON file was provided with demographic and purchasing information about Heroes of Pymoli video game.

Purchasing Analysis by Age Dataframe

For the Purchasing Analysis by Age Dataframe is required to create bins to group all the players by their specific age range. According to criteria applied, the players were divided in the following age range bins:

Less than 10

10-13

14-17

18-21

22-25

26-29

30-33

34-37

38-40

Greater than 40


# Most Popular Items DataFrame

To obtain the most popular items is required to group the records from purchase_data dataframe by Item ID, Item Name columns, create popitems_df dataframe including all required columns (with their proper calculation and formatting), and sort dataframe by Purchase Count column.

To obtain the most popular items is required to group the records from purchase_data dataframe by Item ID, Item Name columns, create popitems_df dataframe including all required columns (with their proper calculation and formatting), and sort dataframe by Total Purchase Value column.




# Data Analysis

Once all the information is collected and organized in dataframes, a data analysis is conducted to identify trends and patterns present in the provided data.


# Data Findings

No one have spent more than $20.00 in the game.
Most purchases are made by men from 18 to 25 years old.
Most popular items prices are below the average item price.
