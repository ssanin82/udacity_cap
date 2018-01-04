# Machine Learning Engineer Nanodegree
## Capstone Proposal
Sergiy Sanin

December 13, 2017

### Domain Background
Price prediction is a highly important task for investment banks and financial institutions. Various statistical models are employed to solve this problem. This project aims to get its take on price prediction - namely, estimating stock price movement for a given time period, given historical price and volume price data. The goal is to try expanding existing stock chart technical analysis techniques with machine learning.

As a software engineer working in an investment bank for past 7 years, I am interested in mastering existing and if exploring new ways to improve and enhance our trading systems using machine learning techniques. This will also help me understand more about the job of quantitative developers and search new ways to collaborate with them.

### Problem Statement
Input:
- Selected stock names to investigate
- Date interval for the stock data
- Stock price (adjusted close) and volume data for the given date range
- Testing interval in percentage of selected time interval (10-50%)

Output:
- Adjusted close price for the given stock during training interval
- Relevant quality measurements

### Datasets and Inputs
20 tech stock tickers to consider from [Yahoo! Finance](https://finance.yahoo.com) (MSFT, GOOGL, YHOO, NFLX, ADBE, TWTR, CSCO, IBM, INTC, AMD, AAPL, AMZN, ORCL, FB, SAP, HP, ACN, INFY, CTSH, EPAM).
The information for the project will be limited to year 2017.

### Solution Statement
The model selected for the problem is neural network, its hyperparameters are the following:
* number of layers (1 or 2)
* number of inputs (days in a row)
* number of outputs (days in a that follow inputs)
* number of units in hidden layer 1
* number of units in hidden layer 2
* activation function selection (sigmoid, relu)

(additional hyperparameters may be added during implementation depending on time available - like, online training vs batch learning and size of batch, different types of neural networks, etc)

*Output* described in problem statement.

### Benchmark Model
As a benchmark polynomial regression model is selected (linear or higher). The result is usually measured using coefficient of determination and MSE metrics.

### Evaluation Metrics
Both coefficient of determination and mean squared error can be used to measure and compare benchmark and solution models. Coefficient of determination will give a normalized value of error between 0 and 1, while mean squared error will give unnormalized error estimate, giving more weight to larger errors.

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

