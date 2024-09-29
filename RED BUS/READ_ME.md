# Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit


## Introduction
* #### The "Redbus Data Scraping and Filtering with Streamlit Application" aims to revolutionize the transportation industry by providing a comprehensive solution for collecting, analyzing, and visualizing bus travel data. By utilizing Selenium for web scraping, this project automates the extraction of detailed information from Redbus, including bus routes, schedules, prices, and seat availability. By streamlining data collection and providing powerful tools for data-driven decision-making, this project can significantly improve operational efficiency and strategic planning in the transportation industry.

## Domain
* #### TRANSPORTATION

## Technologies used
* MySQL
* Python
* Selenium
* Streamlit
  
## Skill takeaways
* Python scripting, Selenium, Data Collection, Data Cleaniing, Data Management using SQL, Streamlit

## FEATURES OF THE APPLICATION

## Retriving Bus Information:
* Selenium is a powerful tool for automating web browsers, which is especially useful for scraping data from dynamic webpages. If you want to retrieve bus details from RedBus, you can use Selenium to automate the process of searching for buses and extracting the relevant information. This involves interacting with web elements like input fields and buttons, waiting for the page to load, and extracting the desired details from the search results.

## Cleaning retrieved data:
* As the data is collected as a pandas dataframe, data cleaning was done by using pandas functions and regular expressions. Cleaned data is also stored as a csv file.

## Storing data in database:
* A MySQL connection is established with the help of mysql.connector module. A new table is created and data was inserted from the dataframe into the table using MySQL. The database could be accessed and managed in the MySQL environment.

## Web app - Streamlit:
* With the help of Streamlit, you can create an interactive application similar to RedBus by designing a user-friendly interface that allows users to search for bus routes, view available buses, and get details like bus names, departure times, arrival times, prices, etc.

## PACKAGES AND LIBRARIES
* import time
* import pandas as pd
* import streamlit as st
* import mysql.connector
* from selenium import webdriver
* from selenium.webdriver.common.by import By
* from streamlit_option_menu import option_menu
* from selenium.webdriver.common.keys import Keys
* from selenium.webdriver import ActionChains as AC
* from selenium.webdriver.support.wait import WebDriverWait
* from selenium.common.exceptions import NoSuchElementException
* from selenium.webdriver.support import expected_conditions as EC