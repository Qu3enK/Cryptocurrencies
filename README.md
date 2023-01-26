# Cryptocurrencies

## Overview
The purpose of the Cryptocurrencies analysis is to analyze the various cryptocurrencies for the senior manager of the Advisory Services Team at Accountability Accounting. They are interested in offering a new cryptocurrency investment portfolio for its customers.  As part of the effort develope a report that includes the cryptocurrencies that are on the trading market and how they could be grouped to create a classification system for this new investment. [^1]



## Summary
In order to analyze the data, we preprocessed the data utilizing Pandas as follows:
  - Reviewed only cryptocurrencies that was being traded
  - Removed null values
  - Retained only cryptocurrencies that were mined
  - Used the `StandardScaler` method to standardize the data

In addition, utilized the `PCA` algorithm to reduce the data dimensions to 3 components and the `K-Means` algorithm to determine the best 'K' value.  Use the 'K' value to assist in predicting the clusters.  Finally using the components and 'K' value to develop an interactive 3-D graph and scatter plot, that allows for the reviewer to hover over specific aspects of the graph and view more detail.




[^1]: Utilize some of description from Module 19 work to assist in writing my background for the Challenge
