# pandas-challenge-1
This is the first pandas challenge. 

The data comes from a csv file of customer names, IDs, order numbers, dates of the order, prices, and costs.

The data is clean.

Created a column for shipping price that is $7/lb for orders>50lbs and $10/lb for orders <= 50lbs.

A tax of 9.25% is added to the total price and shipping cost.

A profit line column is created = price - cost

The dataset is checked by comparing 3 emails that contain the order ID and the total cost.

A summary is created for the top 5 customers by the number of orders - not the number of items.

Some of the data is changed to millions to make the data analysis easier to understand