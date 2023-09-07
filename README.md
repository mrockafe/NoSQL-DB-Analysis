# NoSQL-DB-Analysis
UK Food Standards Database Analysis with NoSQL 

## Description
- In this repository we have created a a full project using pymongo and pandas to perform analysis on a given json database for UK food standards
- To begin we must comit the json database into our mongo via terminal
- Once completed we use Jupyter Lab to pull in the mongo database
- With our database pulled in we may now edit, add, and clean up the database
- Once the data clean in the file "NoSQL_setup_starter.ipynb" is completed we may move to the analysis
- In the "NoSQL_analysis_starter" we perform the analysis
    <br/>1: Create a dataframe for all records with a hygine score equal to 20
    <br/>2: Create a dataframe for all records with a rating value greater than or equal to 4
    <br/>3: Create a dataframe for all records with a rating value of 5 sorted by hygine score
    <br/>4: Create a dataframe for all records grouped by area with a hygine score of 0

## Instructions
- To use this repository you must firt make sure mongo compass and the pymongo library is installed
- Being by importing the json database in the reasourceses folder into mongo via the terminal on your device
- Once completed the jupyter scripts can run from the top starting with "NoSQL_setup_starter.ipynb"
- After this script is ran the data is cleaned and you may run "NoSQL_analysis_starter" from the top
