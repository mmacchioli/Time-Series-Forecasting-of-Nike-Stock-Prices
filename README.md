### Time Series Forecasting of Nike Stock Prices: A Value Investing Perspective

### Introduction to Value Investing Approach
Value investing is based on the belief that stock prices will eventually align with a company's intrinsic value, which is calculated from fundamental financial metrics like sales, profits, margins, and cash flows. Although short-term market prices may be volatile due to various external influences such as news or financial reports, the intrinsic value acts like a gravitational force, steadily pulling the market price towards it over time. This principle suggests that investors should buy stocks when they are undervalued and sell when they are overvalued. 

The gravitational metaphor, illustrated by the interaction between two spheres in the accompanying image, vividly demonstrates how the intrinsic value influences and ultimately guides market prices, asserting that despite temporary deviations, prices will converge on their true economic worth in the long run. This visualization and explanation underscore the core tenet of value investing: market rationality will prevail as prices gravitate towards their fundamental intrinsic values over the long term.

### Objective
The aim of this analysis is to determine the fundamental price of Nike stocks, which acts as a gravitational point drawing the current market price towards it. The primary objective is to estimate this fundamental value and project the time series for the next 24 months, assuming that the fundamental values remain relatively stable. 


### Data

Source and Accessibility

The financial metrics used in this analysis are sourced from stockrow.com, a reliable provider of comprehensive financial data for publicly traded companies. This platform offers a wide array of financial metrics crucial for conducting detailed financial analyses.

![image](https://github.com/user-attachments/assets/da509d1c-4a8f-45c6-b2ba-d90683eecb51)

### Estimation Method

Objective and Approach
To estimate the fundamental price of Nike's stock, we initially identify the most predictive financial metrics. An Ordinary Least Squares (OLS) regression model is then employed, selecting Sells and EBITDA as primary predictors. These metrics were chosen for their significant roles in representing revenue and profitability, respectively.

Statistical Significance and Model Efficacy
The chosen variables are both statistically and economically significant, with the regression model explaining approximately 90% of the variance in Nike's stock price. This high degree of explanation underscores the robustness of the model in capturing key price drivers.

Visual Analysis
The following images display the regression analysis results and the correlation matrix, visually substantiating the strong relationship between the chosen variables and the stock price:

Regression Analysis Results

![image](https://github.com/user-attachments/assets/faa713ed-496d-43be-94b5-0a9b4c5f22aa)

![image](https://github.com/user-attachments/assets/e826f636-30d1-4664-9868-3afdb4a58ae6)

### ARIMA Projections
Using historical stock price data, an ARIMA model will be configured to forecast the price movements for the next two years. This section will detail the selection process for the ARIMA model parameters (p, d, q) and discuss the model’s fit and forecast accuracy. The model's predictions will be compared against the estimated intrinsic values to identify potential periods where the stock might be under- or over-valued.

![image](https://github.com/user-attachments/assets/e1567b7e-915e-4c8e-b3f7-1a2e355914ad)

### Conclusions
The conclusion will summarize the findings from the ARIMA model projections in the context of value investing. It will discuss the potential for Nike's stock to align with its fundamental value over the forecast period and provide investment strategy recommendations based on the predicted price movements. Additionally, it will highlight the limitations of the forecasting model and suggest areas for further research.

