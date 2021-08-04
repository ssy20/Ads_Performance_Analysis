# Ads_Performance_Analysis


## Goal
Given aggregate information about different versions of ad campaigns, analyze their current performance as well as predict their future performance.

The performance of ads is measured based on 
- Click-through-rate (CTR):  # of clicks/ # of impressions
- Profit: revenue from conversions - ad costs
 By setting a threshold for profitability, we can find the ads with highest CTR
 
To predict future performance, a time series model is built to predict the daily number of impressions. Based on the model, the overall trend is going up and there is a small amount of weekly variation.
