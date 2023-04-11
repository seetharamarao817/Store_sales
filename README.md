# Store_sales
Objective : I need to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.The main aim is predicting sales for each product family and store combinations.

There are 54 stores and 33 prodcut families in the data. The time serie starts from 2013-01-01 and finishes in 2017-08-31. However, we already have a splitted data as train and test. The dates in the test data are for the 15 days after the last date in the training data. Date range in the test data will be very important to us while we are defining a cross-validation strategy and creating new features.

There are 6 data that we will study on them step by step.

Train
Test
Store
Transactions
Holidays and Events
Daily Oil Price
The train data contains time series of the stores and the product families combination. The sales column gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).The onpromotion column gives the total number of items in a product family that were being promoted at a store at a given date.

Stores data gives some information about stores such as city, state, type, cluster.

Transaction data is highly correlated with train's sales column. You can understand the sales patterns of the stores.

Holidays and events data is a meta data. This data is quite valuable to understand past sales, trend and seasonality components. However, it needs to be arranged. You are going to find a comprehensive data manipulation for this data. That part will be one of the most important chapter in this notebook.

Daily Oil Price data is another data which will help us. Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices. That's why, it will help us to understand which product families affected in positive or negative way by oil price
