# Time_Series_Project
This project is based on the udemy course. in this project the following will be carried out:
- see the data of different technology companies.
- create a graph with the values of the shares of the companies.
- create an interactive graph with the value of the shares over time
- see the performance of the actions
- create an interactive graph with the performance of the stock over time.
- view the daily performance of stocks
- use the date as an index for the search
- create a graph with the daily, monthly and annual performance of a stock
- create correlation charts with seaborn
- create a heat map to see the correlation between companies
- create performance correlation charts with seaborn
- create a minimum and maximum profit estimate

## Dependencies and library
you need these libraries:
- pandas
- numpy
- matplotlib.pyplot
- seaborn

you must set the variable `path` in the place where to save this file.

like this: `path = /your path / Time series project / individual_stocks_5yr-20210607T205854Z-001 /`
just change the section of "your path"

you can see the variable `path` just below the import of libraries (with a comment that says the following: "# here we expicificate the route of the data")

you need change too the variable df

like this: `df = pd.read_csv(/your path /Time Series Project/individual_stocks_5yr-20210607T205854Z-001/individual_stocks_5yr/AAPL_data.csv)`

you can see the variable just below the title
"Create the variable df"
and finally you need to change the variable paths to aapl, amzn, goog, msft.

like this:

`aapl = pd.read_csv ("/ your path / individual_stocks_5yr-20210607T205854Z-001 / individual_stocks_5yr / AAPL_data.csv")`

`amzn = pd.read_csv ("/ your path / individual_stocks_5yr-20210607T205854Z-001 / individual_stocks_5yr / AMZN_data.csv")`

`goog = pd.read_csv ("/ your path / individual_stocks_5yr-20210607T205854Z-001 / individual_stocks_5yr / GOOG_data.csv")`

`msft = pd.read_csv ("/ your path / individual_stocks_5yr-20210607T205854Z-001 / individual_stocks_5yr / MSFT_data.csv")`

you can see the variable just below the title
"file edit format view help analyse whether stock prices of tech companies are correlated on not"

