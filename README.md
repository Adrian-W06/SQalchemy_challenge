# SQalchemy_challenge
# Introduction
I am composing an analysss to assess the climate of an area i would like to visit in Hawaii.
In order to find an ideal area to settle for vacation, i will gather data of stations in Honolulu, Hawaii. The data will focus on the temparature and precipitation.

# Tables and ORM
Using an sqlite file containing climate data of stations in honolulu, i composed an engine to seach for data in a sql database. Using the create_engine function, i was able to access a database on SQL that had climate information on potential sations.

# Percipitation Analysis
A query was created to access the sqlite database. The query was to collect the date and the percipitation of stations. To make the data readabla, it was converted into a Pandas dataframe.

# Station Analysis
A query was designed to collect a number of stations in the dataset.Then the query was designed to find and sort the stations in descending order.

# API Routes
API routes were esablished. A start route is estblished to find an intial date. A end route is estblished with end date inputs. Then  to find the min, max and average temperatures from a given start date and end date.
