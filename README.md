# challenge3
Arbitrage trading 

## Collect Data
collected the data from two csv files, created two different data frames to sort them; bitstamp_df and coinbase_df

## prepared data
prepared the data by checking for nan's, cleaned up the data by removing '$' from the valuesd in close column and converted the data type of close to float
did this for each data fram

## Anaylzed data
began by focusing on three time frames, one month, one month early, and one month later.
plotted the timeframes to get a more detailed look.

than focused our anaylsis on three specific dates. I chose 01/16/18 , 02/01/18 , and 03/01/18

we used these days to calculated the arbitrage profits. 
 - first we measured the arbirtrage spread by subtracting bitstamp from coinbase, than used conditional statement to generate the summary statistics where the spread was greater than 0.
 - I than calculated the spread returns by dividing the instances that where greater than 0 by the exchange i bought it on.
 - i narrowed down the trading opporutnities to the ones that only returned a 1% minimum ROI. this is to ensure we covered out cost.
 - i than calculated potnetial profits by muliplying the sprad returns that were greater than 1% by that cost of what they where purchased at.
