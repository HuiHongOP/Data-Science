# Data-Science-
This is the homeworks/programs from data science class

# Overview
In this project, the main idea is to explore the dataset on https://data.cityofnewyork.us/Business/License-Applications/ptev-4hud . My goal is to display the different type of bussinesses issued In NYC based on different boroughs. The below questions are going to be answered through data data visualization.

1. Question : What type of business has the highest percentage?
2. Question: Which borough have the most applications?
3. Question: How many are renewal and new applications?
4. Question: What happened to the bussiness during pandemic? Will there be more businesses or less?
I assume that the license applications would decrease due to covid19.

# Data Section
The dataset that is being used on this project is https://data.cityofnewyork.us/Business/License-Applications/ptev-4hud . It contains different information about issuing a business license application across the United States. Will be only interested in the 5 boroughs of NYC.

# Techniques for Data Cleaning :
Dropping out all the nan rows from useful dataframes such as State, Status, Applications, Date, City, and License Category.
Removing information that are not needed in the dataset. (E.g. State: KY, CT, NJ, and ....)
Format the dataset in a good format such as date convert into years(number) instead with month and day on them. Convert datasets into different Boroughs of NYC. Cleaning out the City that are not within the 5 boroughs.
Grouping them by date using pivot table.

# Data visulization:
Using the top 10 of that specific data columns to create pie charts and bar graphs.
Using the years with number of applications to display different boroughs on a line graph.
tools:
libraries such as pandas, datetime and matplotlib.

# Resource Links
https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92 (get dataset from google drive)
#Inspired by https://www.dataquest.io/blog/making-538-plots/ and from hw#15 Coursework
#https://data.cityofnewyork.us/Business/License-Applications/ptev-4hud ( Dataset)
https://pandas.pydata.org/docs/reference/api/pandas.pivot_table.html ( create pivot table)
https://www.sisense.com/blog/data-visualizations-in-python-and-r/ (Data visualization)
https://docs.python.org/3/library/datetime.html ( datetime)
