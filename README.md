# Dates-tidy-up

## Description
This is a start-up project on tidying up the messy date inputs from `Dates.csv` with 3 columns (`Year`, `Month` and `Day`).  

The goal of this project was to practice text wrangling using functions. Therefore, the dates were processed as strings and no third-party packages were used in data cleaning. 

`ggplot2` package is used in the data visualization section. 

## Steps
1. A `check_date()` function that check the validity of the date as a whole. Specifically, it checked for individual input of each column, as well as the validity of the dates as a whole; 
2. A `return_date()` function that used `check_date()` and returned the date in the format of `dd-mm-yyyy` if the date was valid;  
3. Apply the function on the entire data set and saved the output;  
4. A simple data visualization on the output for the distribution of the month.  
