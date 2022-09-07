# Stock-Market-Automatic-Webscraper
I made a program in Jupyter Notebook where the program automatically gets info on Apple’s stock such as the price, rise/decline rate, date, time, etc . 
This automatically happens every 5 minutes (without me running it) so I can run the program once and it will indefinitely produce data about the stock. 
After every 5 minutes of scraping info about the stock, the data goes into a CSV file (which can be trillions of data) . I than use the pandas library to turn the live data into a data frame 
and eventually produce graphs based on the growth/decline of the stock. 

I have also incorporated the time and datatime library to gather the current time and this will be used to be able to determine when the function, 
I’ve made to calculate the stock’s data, should run: 9:30 am till 4 pm, Monday through Friday. Thus, I’ve set the program to update the info every 5 minutes, 
so roughly 78 prices (6.5 hours, 5 minute intervals) will be added to the data frame every day, more than enough data. 

Obviously, I cannot run a year's worth of data yet because the program would have to run for 1 year continuously, but the csv file shows a small glimpse of the data extracted for 160 minutes of the program running and how it is organized into a data frame

This can be expanded to multiple stocks in an industry, such as Technology where I have info from Samsung, Microsoft, Facebook, etc. 
With this, I could compare different stocks from the same industry to see what would produce the best profits, in terms of the percentage increases. 

An even bigger expansion to this program is to generate the data with all stocks in the stock market. 
At the end of every month, the program would efficiently illustrate the top (most profitable) stocks to have invested in for the month. 
To figure what would be the best stock, the highest percentage increase in price from day 1 to the last/given day would result in the best profit yielded.
