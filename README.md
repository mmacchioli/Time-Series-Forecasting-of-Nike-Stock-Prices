### Time Series Forecasting of Nike Stock Prices: A Value Investing Perspective

This project applies value investing finance theory to estimate the fundamental price of Nike stocks, acting as a gravity force that trends the prices in the long run. Important and successful value investors such as Warren Buffett and Peter Lynch apply this method

### Introduction to Value Investing Approach
Value investing is based on the belief that stock prices will eventually align with a company's intrinsic value, which is calculated from fundamental financial metrics like sales, profits, margins, and cash flows. Although short-term market prices may be volatile due to various external influences such as news or financial reports, the intrinsic value acts like a gravitational force, steadily pulling the market price towards it over time. This principle suggests that investors should buy stocks when they are undervalued and sell when they are overvalued. 

The gravitational metaphor, illustrated by the interaction between two spheres in the accompanying image, vividly demonstrates how the intrinsic value influences and ultimately guides market prices, asserting that despite temporary deviations, prices will converge on their true economic worth in the long run. 

This visualization and explanation underscore the core tenet of value investing: market rationality will prevail as prices gravitate towards their fundamental intrinsic values over the long term.

![image](https://github.com/user-attachments/assets/fd668fde-35c7-47fa-bff0-8cf76f52fdd1)


### Objective
The aim of this analysis is to determine the fundamental price of Nike stocks, which acts as a gravitational point drawing the current market price towards it. The primary objective is to estimate this fundamental value and project the time series for the next 24 months, assuming that the fundamental values remain relatively stable. 


### Data

Source and Accessibility

The financial metrics used in this analysis are sourced from stockrow.com, a reliable provider of comprehensive financial data for publicly traded companies. This platform offers a wide array of financial metrics crucial for conducting detailed financial analyses.

![image](https://github.com/user-attachments/assets/da509d1c-4a8f-45c6-b2ba-d90683eecb51)

### Estimation Method

Objective and Approach
To estimate the fundamental price of Nike's stock, we initially identify the most predictive financial metrics. An Ordinary Least Squares (OLS) regression model is then employed, selecting Sales and EBITDA as primary predictors. These metrics were chosen for their significant roles in representing revenues and profitability, respectively.

Statistical Significance and Model Efficacy
The chosen variables are both statistically and economically significant, with the regression model explaining approximately 90% of the variance in Nike's stock price. This high degree of explanation underscores the robustness of the model in capturing key price drivers.

Visual Analysis
The following images display the regression analysis results and the correlation matrix, visually substantiating the strong relationship between the chosen variables and the stock price:

Regression Analysis Results

![image](https://github.com/user-attachments/assets/3830081a-c501-43b5-8a4d-ec83f8adcebf)

![image](https://github.com/user-attachments/assets/2e99cb4f-ea68-4771-b1e9-b5d9050238d7)

Finally, we apply the Hodrick-Prescott filter to isolate the trend components within the Sales and EBITDA series. These components are then utilized to estimate a linear projection in our OLS model. This method facilitates an effective evaluation of these trends, enabling us to accurately predict the fundamental price of Nike stocks

![image](https://github.com/user-attachments/assets/9933ec67-2917-45ac-b4fb-47499bdfe5ef)

### ARIMA Projections
Using Fundamental stock price data, an ARIMA model will be configured to forecast the price movements for the next two years. This section will detail the selection process for the ARIMA model parameters (p, d, q) and discuss the model’s fit and forecast accuracy. The model's predictions will be compared against the estimated intrinsic values to identify potential periods where the stock might be under- or over-valued.

To select the appropriate ARIMA model, we utilize the auto.arima function in RStudio, which determines the optimal ARIMA order by minimizing the AIC criterion

[ARIMA Models: https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average]

![image](https://github.com/user-attachments/assets/5993e7cc-1182-47c4-a7d4-173961eac5bd)

### Results and conclusions

The analysis results show that, over the last year, Nike's stock price has been significantly lower than its fundamental values. According to value investing theory, this presents a good opportunity to buy Nike stock at the current price due to the substantial safety margin it offers. Furthermore, if the sales and EBITDA remain relatively stable, the continued decline in current prices could present an even more compelling buying opportunity.

![image](https://github.com/user-attachments/assets/e1567b7e-915e-4c8e-b3f7-1a2e355914ad)



