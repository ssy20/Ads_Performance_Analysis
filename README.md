# Ads_Performance_Analysis


## Goal
Given aggregate information about different versions of ad campaigns, analyze their current performance as well as predict their future performance.

The performance of ads is measured based on 
- Click-through-rate (CTR):  # of clicks/ # of impressions
- Profit: revenue from conversions - ad costs
 By setting a threshold for profitability, we can find the ads with highest CTR
 <img src=img.png width="400" height="250">

To predict future performance, a time series model is built to predict the daily number of impressions. Based on the model, the overall trend is going up and there is a small amount of weekly variation.

## Data
For each version of ad campaign, the dataset includes:
- ad : categorical variable, representing different versions of ad campaigns
- date:  data are aggregated daily
- shown: the number of ads shown on the web
- clicked : the number of clicks on the ads
- converted : the number of conversions on the site coming from ads
- avg_cost_per_click : on an average, how much it cost each of those clicks
- total_revenue : the revenue came from the conversions
