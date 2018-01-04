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
20 tech stock tickers considered from [Yahoo! Finance](https://finance.yahoo.com) (MSFT, GOOGL, YHOO, NFLX, ADBE, TWTR, CSCO, IBM, INTC, AMD, AAPL, AMZN, ORCL, FB, SAP, HP, ACN, INFY, CTSH, EPAM).
The information for the project will be limited to year 2017.

### Solution Statement
The model selected for the problem is neural network, its hyperparameters are the following:
* number of layers (1 or 2)
* number of inputs (days in a row)
* number of outputs (days in a that follow inputs)
* number of units in hidden layer 1
* number of units in hidden layer 2
* activation function selection (sigmoid, relu)

(additional may be added during implementation - like, online training vs batch learning and size of batch, etc)

*Output* described in problem statement.

### Benchmark Model
As a benchmark linear prediction model is selected.

TODO: provide details.

_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
