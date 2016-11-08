# 2016 US Presidential Election Forecast

## SAFE Model

For fun, I put together a very, very simply model using the forecasts produced by the six major forecasters (i.e. PEC, 538, The Upshot, DailyKos, PredictWise, and The Huffington Post). SAFE stands for Simple Averaged Forecasters Estimate. Data is collected from The Upshot using my `pres_forecast` function (see [here](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/README.md)). SAFE generates a forecast by simply averaging the probability of a candidate winning a state across the six major forecasters, then multiplies that averaged probability with that state's electoral votes. Summing the estimated electoral votes across states for each candidate gives us a very simple model of what the election outcome might look like.

## Final Prediction (X:XXam EST on November 8, 2016)

Election Day is here, and the final SAFE model shows Hillary Clinton winning the election with an estimated XXX electoral votes to Donald Trump's XXX.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/estimated_electoral_votes_2016-11-07.png?raw=true)

On average, Clinton can currently win 268 electoral votes in states where she has a greater than 90% probability of victory, so essentially she needs to capture just one state where he chances are less than 90% to secure the presidency.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_2016-11-07.png?raw=true)

There was continued weakening in Clinton's chances in North Carolina and New Hampshire across many of the major forecasters. 

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NC_2016-11-07.png?raw=true)

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NH_2016-11-07.png?raw=true)

These states represent two of the five where the major forecasters differ the most; North Carolina has a standard deviation of .1703 across the six major forecasters, while New Hampshire has a standard deviation of .1302.

One of the other ways Clinton can win is by taking Nevada's 6 electoral votes. Clinton has a 63.8% chance of winning Nevada, based on an average of the major forecasters, a decline of 4.4% since last week. Nevada is also one of the states where the major forecasters disagree the most, with a standard deviation of .1588.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NV_2016-11-07.png?raw=true)

Full table with average probabilities and standard deviations can be found [here](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/Average%20and%20Standard%20Deviation%20Across%20Forecasters.csv).

## Previous Updates

### November 7, 2016

With one day to go until the election, SAFE shows Hillary Clinton maintaining her lead over Donald Trump, with an estimated 312 electoral votes going to the Democratic Party's candidate. 

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/estimated_electoral_votes_2016-11-07.png?raw=true)

On average, Clinton can currently win 268 electoral votes in states where she has a greater than 90% probability of victory, so essentially she needs to capture just one state where he chances are less than 90% to secure the presidency.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_2016-11-07.png?raw=true)

There was continued weakening in Clinton's chances in North Carolina and New Hampshire across many of the major forecasters. 

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NC_2016-11-07.png?raw=true)

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NH_2016-11-07.png?raw=true)

These states represent two of the five where the major forecasters differ the most; North Carolina has a standard deviation of .1703 across the six major forecasters, while New Hampshire has a standard deviation of .1302.

One of the other ways Clinton can win is by taking Nevada's 6 electoral votes. Clinton has a 63.8% chance of winning Nevada, based on an average of the major forecasters, a decline of 4.4% since last week. Nevada is also one of the states where the major forecasters disagree the most, with a standard deviation of .1588.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NV_2016-11-07.png?raw=true)

### November 5, 2016

As of November 5th, SAFE is estimating that Hillary Clinton will win 314 electoral votes to Donald Trump's 224. 

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/estimated_electoral_votes_2016-11-05.png?raw=true)

Clinton's lead has declined over the past week. On 11/1, SAFE estimated she would win 328 electoral votes. While FiveThirtyEight has moved the most aggresively towards Trump, Clinton's lead has softened in most of the major forecasts.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_2016-11-05.png?raw=true)
![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/compare_forecasters_2016-11-05.png?raw=true)

Clinton has seen her probability of winning North Carolina and New Hampshire decline significantly over the past few days.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NC_2016-11-05.png?raw=true)

Clinton's chances in North Carolina have declined to 70.4% across the major forecasters, down 12 percentage points since November 1st. 

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/trend_NH_2016-11-05.png?raw=true)

Clinton has also seen a similar steep decline in New Hampshire, where she is now 81% to take the state, down from 92.6% just five days ago.

