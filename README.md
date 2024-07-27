### Time Series Forecasting of Nike Stock Prices: A Value Investing Perspective

### Introduction to Value Investing Approach
Value investing is based on the belief that stock prices will eventually align with a company's intrinsic value, which is calculated from fundamental financial metrics like sales, profits, margins, and cash flows. Although short-term market prices may be volatile due to various external influences such as news or financial reports, the intrinsic value acts like a gravitational force, steadily pulling the market price towards it over time. This principle suggests that investors should buy stocks when they are undervalued and sell when they are overvalued. 

The gravitational metaphor, illustrated by the interaction between two spheres in the accompanying image, vividly demonstrates how the intrinsic value influences and ultimately guides market prices, asserting that despite temporary deviations, prices will converge on their true economic worth in the long run. This visualization and explanation underscore the core tenet of value investing: market rationality will prevail as prices gravitate towards their fundamental intrinsic values over the long term.

![image](https://github.com/user-attachments/assets/e53532ab-a6bc-40bb-a363-b264a8d5e07f)


### Objective
The aim of this analysis is to determine the fundamental price of Nike stocks, which acts as a gravitational point drawing the current market price towards it. The primary objective is to estimate this fundamental value and project the time series for the next 24 months, assuming that the fundamental values remain relatively stable.

### Estimation Method
To estimate the intrinsic value of Nike, we will utilize a combination of financial analysis techniques including Discounted Cash Flow (DCF) and Price/Earnings to Growth (PEG) ratios. These methods will help quantify the true value based on Nike’s financial health and growth prospects. For the time series forecasting, the ARIMA model will be employed to predict future stock prices based on historical price data, adjusted for estimated fundamental values.

### ARIMA Projections
Using historical stock price data, an ARIMA model will be configured to forecast the price movements for the next two years. This section will detail the selection process for the ARIMA model parameters (p, d, q) and discuss the model’s fit and forecast accuracy. The model's predictions will be compared against the estimated intrinsic values to identify potential periods where the stock might be under- or over-valued.

### Conclusions
The conclusion will summarize the findings from the ARIMA model projections in the context of value investing. It will discuss the potential for Nike's stock to align with its fundamental value over the forecast period and provide investment strategy recommendations based on the predicted price movements. Additionally, it will highlight the limitations of the forecasting model and suggest areas for further research.

