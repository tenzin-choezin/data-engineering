# Data Engineering Projects

These are a collection of data engineering projects that I completed as part of UC Berkeley's recently created CS 194 - Data Engineering course. 

An overview of the projects in this repo:
- **sql_exploration.ipynb:** Working with SQL on the IMDB database
- **query_performance.ipynb:** Exploring how the database system optimizes query execution and how users can futher tune the performance of their queries. This project works with the Lahman's Baseball Database, an open source collection of baseball statistics from 1871 to 2020. It contains a variety of data, like batting statistics, team stats, managerial records, Hall of Fame records, and much more.
- **data_transformation.ipynb:** Dealing with one month of data from sensors in buildings at UC Berkeley. This is a very typical real-world dataset in that it's kind of a mess. The full dataset contains a giant `data` table of sensor readings that is many billions of readings over the course of a decade; we will look at a single month of that data. It also contains a variety of other tables that contextualize the readings.
- **mongo_analysis.ipynb:** Investigating how different database systems handle semi-structured JSON data. In particular, we will be placing emphasis on the use of MongoDB: a database system that stores data in a construct known as documents. In this project, we will be working with the Yelp Academic Dataset which contains a dataset of `businesses`, `reviews`, and `users`. Due to the limitations of JupyterHub and the Mongo instances we are working with, `reviews` and `users` are truncated to 7500 reviews and 1000 users. We will be using the full `businesses` dataset, however.
