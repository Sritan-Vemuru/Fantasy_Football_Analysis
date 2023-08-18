# Fantasy_Football_Analysis

Basic data analysis and visualization of fantasy football statistics

## Description

This project allowed me to analyze fantasy football statistics while learning about the basics of web scraping using BeautifulSoup, data cleaning and analysis using NumPy and Pandas, and data visualization using Matplotlib. The goal of this project was to make predictions for the average number of points scored for the top 10 running backs and the top 10 wide receivers for the 2023 fantasy football season. I first web-scraped all the statistics I needed from https://www.pro-football-reference.com/years/2022/fantasy.htm from 2002 to 2022 using BeautifulSoup. After parsing the files and getting the table I needed, I made a data frame containing only the top 10 wide receivers and running backs according to PPR scoring. I then made a second data frame with all the averages for each year, and I plotted them as line graphs. I then got a line of best fit for both the wide receiver data and the running back data, and I made my 2023 predictions using the lines of the best fit.

### Dependencies

This program uses Pandas, NumPy, Matplotlib, and BeautifulSoup.

## Conclusions

The conclusions I drew from this project are that over the past two decades, the amount of fantasy points scored by the top running backs continues to decrease while the amount of fantasy points scored by top wide receivers continues to increase. The 2023 prediction for the average points scored by the top 10 wide receivers in PPR scoring is 293.87 and for running backs, it is 268.10. 
