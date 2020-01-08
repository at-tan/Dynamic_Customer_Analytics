# Dynamic_customer_analytics
Data engineering and panel data modelling of the online retail dataset covering transactions made from a UK online wholesaler between December 2010 and December 2011.

Using Python, I constructed a dynamic RFM model providing monthly Recency, Frequency and Monetary scores for each customer based on their evolving behavior. To do so, I aggregated the original intraday data into daily frequency initially, and then into monthly frequency. Monthly periodicity was identified as the optimal frequency for customer analytics in this case. The code for this are contained in "dynamic_rfm_I" and "dynamic_rfm_II".

I subsequently used panel data modelling to fashion RFM composite indicators, to target first customer spending and second the incidence of customer transactions. I then subjected the RFM model to hypothesis tests, which confirmed its usefulness in measuring the customer metrics of choice. The code for this are in "dynamic_rfm_III".

A detailed description of the research methodology and model findings are presented in:
https://medium.com/@a.tzytien.tan/dynamic-customer-analytics-i-9135b2a8854b
