### Time Series Forecasting of Nike Stock Prices: A Value Investing Perspective

### Introduction to Value Investing Approach
Value investing is predicated on the assumption that stock prices will eventually align with the underlying intrinsic value of the company. This intrinsic value is derived from fundamental variables such as sales, profits, margins, costs, and Free Cash Flow, among others. In the short term, market prices can be highly volatile, often swayed by news events or financial reports. However, over the long term, it is expected that prices will gravitate towards their intrinsic value, restoring market rationality. The value investing philosophy supports the notion that a shrewd investor should purchase stocks when their prices are below intrinsic value and sell them when prices are excessively high compared to the fundamental value. 

As illustrated in the accompanying image, the fundamental value of a stock acts much like a gravitational force within the financial markets. In this metaphor, the fundamental value is represented by the larger sphere, which significantly distorts the space around it, symbolizing the economic "fabric" of the market. The smaller sphere, representing the current market price, moves along this curved space, inevitably drawn towards the larger sphere. Over time, external factors may cause the smaller sphere to deviate from its path, but the persistent pull of the fundamental value guides it back, ensuring that over the long term, the price reflects the true economic worth of the company.

This image helps us visualize the powerful influence that fundamental value exerts on stock prices, supporting the core principle of value investing: in the long run, market prices will converge towards their intrinsic values, despite short-term fluctuations driven by market sentiment, news, and other transient factors.

![image](https://github.com/user-attachments/assets/e53532ab-a6bc-40bb-a363-b264a8d5e07f)


### Objective
The aim of this analysis is to determine the fundamental price of Nike stocks, which acts as a gravitational point drawing the current market price towards it. The primary objective is to estimate this fundamental value and project the time series for the next 24 months, assuming that the fundamental values remain relatively stable.

### Estimation Method
To estimate the intrinsic value of Nike, we will utilize a combination of financial analysis techniques including Discounted Cash Flow (DCF) and Price/Earnings to Growth (PEG) ratios. These methods will help quantify the true value based on Nike’s financial health and growth prospects. For the time series forecasting, the ARIMA model will be employed to predict future stock prices based on historical price data, adjusted for estimated fundamental values.

### ARIMA Projections
Using historical stock price data, an ARIMA model will be configured to forecast the price movements for the next two years. This section will detail the selection process for the ARIMA model parameters (p, d, q) and discuss the model’s fit and forecast accuracy. The model's predictions will be compared against the estimated intrinsic values to identify potential periods where the stock might be under- or over-valued.

### Conclusions
The conclusion will summarize the findings from the ARIMA model projections in the context of value investing. It will discuss the potential for Nike's stock to align with its fundamental value over the forecast period and provide investment strategy recommendations based on the predicted price movements. Additionally, it will highlight the limitations of the forecasting model and suggest areas for further research.

