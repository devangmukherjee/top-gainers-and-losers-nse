# top-gainers-and-losers-nse
This is a python script which gives the stocks which gives the top gainers and loser stocks of nse of a given day and stores the information in a csv file along with other useful info like ohlc and volume for further usage.

Install the following libraries:-
-nsetools,pprint,csv

The code originally stores the names of the code in two seperate csv files topGainers.csv and topLosers.csv 

The csv file will contain the following information
-Stock name, open price, high price, low price, previous price, volume, ltp


Incase you need only the stock's name for your code it is available as a list named # stock_list.
You need to comment the append to csv lines to just receive the list a=without creating any csv file, or you can import the list to your desired location.

There many fields that can be obtained from nsetools library for further information please refer the dicumentation:
https://nsetools.readthedocs.io/en/latest/
