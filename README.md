Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit

Introduction:

The "Redbus Data Scraping and Filtering with Streamlit Application" offers an innovative solution to transform the transportation industry by automating the collection, analysis, and visualization of bus travel data. Leveraging Selenium for web scraping, the project extracts critical information from Redbus, such as bus routes, schedules, prices, and seat availability. By simplifying data collection and providing robust tools for data-driven insights, this application enhances operational efficiency and supports strategic planning, empowering stakeholders to make more informed decisions in the transportation sector.

TECHNOLOGY USED:

Python

MySQL

Streamlit

Selenium

Store data in database:

The collected bus details data was transformed into pandas dataframes. Before that, a new database and tables were created using the MySQL connector. With the help of MySQL, the data was inserted into the respective tables. The database could be accessed and managed in the MySQL environment.

web app - streamlit:

With the help of Streamlit, you can create an interactive application similar to RedBus by designing a user-friendly interface that allows users to search for bus routes, view available buses, and get details like departure times and prices

PACKAGES AND LIBRARIES:

pandas as pd

mysql.connector

import time

streamlit as slt

import datetime

from streamlit_option_menu import option_menu

from selenium import webdriver

