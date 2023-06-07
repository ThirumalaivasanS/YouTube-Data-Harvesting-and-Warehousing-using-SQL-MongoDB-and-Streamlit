
# YouTube Data Harvesting and Warehousing 

This project enables users to harvest, store, and analyze data from YouTube channels using Streamlit, Google API, MongoDB, and SQL. This user-friendly application extracts channel information, stores it in a MongoDB data lake, migrates it to a SQL data warehouse, and allows for efficient data search and analysis through SQL queries.




## Prerequisites
To run this project, you need to have Python 3.x installed on your system along with the following libraries:
1. streamlit
2. pandas
3. numpy
4. pymongo
5. mysql-connector-python
6. google-api-python-client








## Necessary imports
1. import streamlit as st
2. import pandas as pd
3. import numpy as np
4. import pymongo
5. import mysql.connector as sql
6. from googleapiclient.discovery import build
7. from googleapiclient.errors import HttpError
8. import json



## ## Project Overview
Once the application is running, you can use it to fetch , save , migrate and analyze the data of a desired YouTube channel.

- user provides a YouTube channel ID as input to the project.
- The project utilizes the YouTube API to fetch channel information associated with the provided channel ID.
- The fetched data is displayed in a JSON format using Streamlit, providing a user-friendly interface.
- The project stores the data in a MongoDB Atlas database, segregating it into distinct collections.
- Users can select a channel from the saved data in MongoDB Atlas to migrate the data to a MySQL database using SQL queries.
- Once the data is migrated to MySQL, users can analyze it by executing SQL queries through Streamlit, facilitating data exploration and generating valuable insights.

## ## Project Overview
Once the application is running, you can use it to fetch , save , migrate and analyze the data of a desired YouTube channel.

- user provides a YouTube channel ID as input to the project.
- The project utilizes the YouTube API to fetch channel information associated with the provided channel ID.
- The fetched data is displayed in a JSON format using Streamlit, providing a user-friendly interface.
- The project stores the data in a MongoDB Atlas database, segregating it into distinct collections.
- Users can select a channel from the saved data in MongoDB Atlas to migrate the data to a MySQL database using SQL queries.
- Once the data is migrated to MySQL, users can analyze it by executing SQL queries through Streamlit, facilitating data exploration and generating valuable insights.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

Contributions are always welcome!

## Credits
This script was created by Thirumalaivasan S.Feel free to modify and use it for your own purposes. If you have any questions or suggestions, please contact me at thirumalaivasan.subramanian@gmail.com