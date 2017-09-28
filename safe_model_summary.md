# 2016 US Presidential Election Forecast

## SAFE Model

For fun, I put together a very, very simply model using the forecasts produced by the six major forecasters (i.e. PEC, 538, The Upshot, DailyKos, PredictWise, and The Huffington Post). SAFE stands for Simple Averaged Forecasters Estimate. Data is collected from The Upshot using my `pres_forecast` function (see [here](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/README.md)). SAFE generates a forecast by simply averaging the probability of a candidate winning a state across the six major forecasters, then multiplies that averaged probability with that state's electoral votes. Summing the estimated electoral votes across states for each candidate gives us a very simple model of what the election outcome might look like.

## Election Results

In what has to be one of the most stunning results in US political history, Donlad Trump flipped a number of blue states to capture the presidency. There are a few states that are yet to be officially called, but as of 7:00am EST Trump had captured 279 electoral votes to Hillary Clinton's 218. Trump managed to flip at least five states from 2012, including Florida, Ohio, and most surprisingly Pennsylvania. 

Of course, the major question coming out of this year's election is how public polls at the state level were so wrong, collectively. Trump won, or is on pace to win, a number of states where Clinton had an average chance of victory over 90%. In some of these cases, Trump never led in any public poll leading up to the election. 

For now, it appears that Clinton's lack of alternative routes to 270 was what did her in. 

Clinton would have captured 268 electoral votes in states where she had a >= 90%+ of winning, but after that there were only five states where she was the favorite:

New Hampshire (4) 81%
Florida (29) 74.6%
Nevada (6) 71.8%
North Carolina (15) 63.6%
Maine CD-2 (1) 52.2%

This means that if Trump were able to flip what was previously thought to be a solid blue state, Clinton would have limited options to make up those votes. And that is essentially what happened. 

The loss of Ohio was expected (she only had an average chance of 32.6% to win it), but when Florida went to Trump that left Clinton with only 26 likely electoral votes to make up any ground. 

As the returns flowed in it became clear that Michigan was in play. The same for Wisconsin and Pennsylvania. These three states represent 16, 10, and 20 electoral votes, respecitvely, and all three were 91% or better to vote for Clinton. Losing any one of those three would have been hard enough to make up for, but losing two for sure (Michigan has yet to be called) as well as Florida exposed the lack of options for Clinton.

In terms of the major forecasters, FiveThirtyEight caught a lot of heat leading up to the election for how bearish their model appeared to be on Clinton. They were a clear outlier, not just at the national level, but for many key states. As of this morning, they appear to have been the most accurate when measured by Brier Scores at the state level:

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/brier_scores_2016-11-09%2007:05:21.png?raw=true)

These Brier Scores take into account the last eight days of predictions and are averaged over those eight days for each forecaster.

## Final Prediction (7:00am EST on November 8, 2016)

Election Day is here, and the final SAFE model shows Hillary Clinton winning the election with an estimated 314 electoral votes to Donald Trump's 224.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/estimated_electoral_votes_2016-11-08.png?raw=true)

As before, Clinton can currently win 268 electoral votes in states where she has a greater than 90% probability of victory, so essentially she needs to capture just one state where he chances are less than 90% to secure the presidency.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_2016-11-08.png?raw=true)

Running the SAFE model on each major forecaster produces a range of outcomes for Clinton, from 303 electoral votes based on FiveThirtyEight to 324 based on the Huffington Post.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/SAFE_by_forecaster_2016-11-08.png?raw=true)

If Clinton were to win each of the states where she currently has an average probability over 50% she would capture 323 electoral votes.

Clinton's chances rebounded in three critical states in the final day of polling.

Her probability of victory increased in New Hampshire to 81% (+4.8%), in Florida to 74.6% (+3.2%), and in Nevada to 71.8% (+8%). 

Full table with average probabilities and standard deviations can be found [here](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/Average%20and%20Standard%20Deviation%20Across%20Forecasters.csv).

_**Note:**_ *Probabilities for the congressional districts in Maine and Nebraska where not available from DailyKos.*

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

