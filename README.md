# Stock-Market-Automatic-Webscraper
I made a program in Jupyter Notebook where the program automatically gets info on Apple’s stock such as the price, rise/decline rate, date, time, etc . 
This automatically happens every 5 minutes (without me running it) so I can run the program once and it will indefinitely produce data about the stock. 
After every 5 minutes of scraping info about the stock, the data goes into a CSV file (which can be trillions of data) . I then use the pandas library to turn the live data into a data frame 
and eventually produce graphs based on the growth/decline of the stock. 

I have also incorporated the time and datatime library to gather the current time and this will be used in order to determine when to calculate the stock’s data: 9:30 am till 4 pm, Monday through Friday. Thus, I’ve set the program to update the info every 5 minutes. 
Roughly 78 prices (6.5 hours, 5 minute intervals) will be added to the dataframe every day.

Obviously, I cannot run a year's worth of data yet because the program would have to run for 1 year continuously, but the csv file attached shows a small glimpse of the data extracted when the program ran for 160 minutes.

This idea can be expanded to different types of stocks in an industry, such as Technology where the program can webscrape information from stocks like Samsung, Microsoft, Facebook etc. 
Using this function/program, I can compare different stocks from the same industry to see what would produce the best profits - in terms of percentage increases. 

An even bigger expansion of this program is to generate the data with all stocks in the stock market. 
At the end of every month, the program would efficiently illustrate the top (most profitable) stocks to have invested in for the month. 
To figure out what would be the best stock, the highest percentage increase in price from day 1 to the last/given day would result in the best profit yielded.
