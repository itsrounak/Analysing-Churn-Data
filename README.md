# Analysing-Churn-Data


Customer churn time is the length of time a customer stays with a company before leaving. This is a vital metric in many businesses and there is great interest in estimating it.
The churn time changes, so we always want to estimate it with the most recent data available. This is statistically challenging as many (hopefully most) customers will have not churned at the time when the data is collected. This means that customer churn data is highly censored.
In this assignment we are going to look into aspects of analysing churn data.


We will be interested in 3 columns:
• months_active: The churn time
• churned: The censoring indicator that is 1 if the customer churned and 0 if the measurement is censored
(aka they were still customers when the data was pulled)
• company_size: A categorical variable with the size of the client’s company.
