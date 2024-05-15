# Improve database performance

Hypertables are PostgreSQL tables with special features that make it easy to handle time-series data. 
Anything you can do with regular PostgreSQL tables, you can do with hypertables. 
In addition, Hypertables give improved performance and user experience for time-series data.

You can compress time-series data to reduce the amount of storage required, and increase the speed of some queries. 

This app shows you how to 


When new data is added to your database, it is in the form of uncompressed rows. Timescale uses a built-in job scheduler to convert this data to the form of compressed columns. This occurs across chunks of Timescale hypertables.