# Project Title
## Portfolio Analysis with Python <br>
# Contents
[Info](#Info)<br>
[Portfolio Analysis and Optimization](#Portfolio-Analysis-and-Optimization)<br>
[Disclaimer](#Disclaimer)
# Info
## Programming Language: 
Python <br>
## Libraries used:
[Pandas](https://pandas.pydata.org/#:~:text=pandas%20is%20a%20fast,%20powerful,%20flexible)<br>
[Numpy](https://numpy.org/)<br>
[Yfinance](https://pypi.org/project/yfinance/)<br>
[Datetime](https://docs.python.org/3/library/datetime.html)<br>
[Scipy](https://scipy.org/)<br>
[Openpyxl](https://pypi.org/project/openpyxl/#:~:text=openpyxl%20is%20a%20Python%20library%20to)<br>
[Xlsxwriter](https://pypi.org/project/XlsxWriter/#:~:text=XlsxWriter%20is%20a%20Python%20module%20for)<br>

# Portfolio Analysis and Optimization
## How to use
Install the necessary libraries mentioned above<br>
Run the program <br>
Select portfolio analysis or portfolio optimization <br>
Enter the tickers of the stocks (and the corresponding weights in case you selected portfolio analysis)<br>
Press 'OK'<br>


## How it works
### Portfolio Analysis
The code entails: <br>
Creating a GUI (Graphic User Interface) where the user enters the tickers of the stocks and the wcorresponding weights<br>
Pulling data from yahoo finance via the yfinance Python library <br>
Calculating the monthly returns <br>
Calculating the average monthly return and the monthly standard deviation of each stock <br>
Calculating the portfolio's expected return and standard deviation<br>
Calculating the sharpe ratio<br>
Creating the correlation matrix<br>
Obtaining the portfolio's beta and R square through a linear regression(the S&P500 index serves as the market portfolio)<br>
Saving all the data as an excel file <br>

### Portfolio Optimization 
The code entails:<br>
Creating a GUI (Graphic User Interface) where the user enters the tickers of the stocks<br>
Pulling data from yahoo finance via the yfinance Python library <br>
Calculating the monthlyy returns <br>
Calculating the average monthly return and the monthly standard deviation of each stock <br>
Identifying the optimal portfolio ie the one that maximizes the sharpe ratio.<br>
In order to achieve that, it employes an optimization technique found in the scipy library <br>
Analyzing the optimal portfolio as described above <br>


## Example

![Στιγμιότυπο οθόνης 2024-11-07 132744](https://github.com/user-attachments/assets/223628c8-d905-4a36-a9ff-068590737ffa)


![Στιγμιότυπο οθόνης 2024-11-07 215015](https://github.com/user-attachments/assets/bf4ad554-ef67-48d7-aadd-5f18998f8ec5)


![Στιγμιότυπο οθόνης 2024-11-07 215004](https://github.com/user-attachments/assets/477634eb-f917-4132-9d94-19785e443d3e)

Notes:<br>
The sharpe ratio is calculated with monthly values.<br>
We consider the risk free rate and the inflation rate to be 2%<br>
These values can be changed in the code

# Disclaimer<br>
This project serves educational purposes only. Under no circumstances should it be used as an actual investment tool.
