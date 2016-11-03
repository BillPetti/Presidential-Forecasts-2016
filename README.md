# Presidential-Forecasts-2016
Function to scrape, format, and plot forecaster data for the 2016 U.S. Presidential Election

## How to use the `pres_forecasts` function

The `pres_forecasts` function will first scrape the state-level forecasts aggregated by The Upshot:

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/Screen%20Shot%202016-11-02%20at%2010.01.05%20AM.png?raw=true)

After scraping the data, the function will extract the numerical data from each state/forecaster cell, melt the data, and then create variables for the numerical probability of a Democratic and Republican victory for each state/forecaster combination.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/Screen%20Shot%202016-11-02%20at%2010.02.39%20AM.png?raw=true)

The data is then re-cast so that average probabilities can be calculated across the six forecasters. This is done for both parties, with cumulative electoral votes calculated sorted by the probability of a party winning a state. A date column is also added.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/Screen%20Shot%202016-11-02%20at%2010.06.20%20AM.png?raw=true)

Three plots are also provided. The first plots the cumulative probability for each party in a faceted chart, with a dashed horizontal line plotted at 270 electoral votes. The second plot simply combines both parties into one chart. And, finally, the third plots each of the forecasters in a comparative way based on data from the current date.

![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_facet_2016-11-02.png?raw=true) 
![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/cumulative_ev_2016_2016-11-02.png?raw=true)  
![alt text](https://github.com/BillPetti/Presidential-Forecasts-2016/blob/master/compare_forecasters_2016-11-03.png?raw=true)

The function will also assign the plots and two main data sets to the Global Environment as well as exporting them to the working directory with a unique name based on the date the function was run.


