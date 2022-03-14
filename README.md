# Stock-Simulation
Built for Google Sheets. Set of functions to run a basic simulation of a market (not representative of an actual stock market). 

Directions:
Copy the .txt files into seperate functions for Google Sheets.
1. Run Initialize() once to set up the spreadsheet.
2. Run the DailyStocks() function after to run the algorithm. You can also set a timer on the function to run automatically.

How it works:
Values fluctuate on a risk-based system: 
High-risk
Medium-risk 
Low-risk

Higher the risk means potentially more gained in returns, as well as more lossed. 
Whereas, Low-risk is meant for passive income with mild fluctuations.

Values fluctuate randomly and are dependent on the length of the streak (gain or loss).
i.e. if the market increases twice in a row, a separate multiplier will adjust the value by which it increases.
