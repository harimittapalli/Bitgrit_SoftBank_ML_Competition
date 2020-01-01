# Bitgrit_SoftBank_ML_Competition
### SoftBank Forex Algorithm Challenge: Develop foreign exchange risk management and trading algorithms

Recently Bitgrit has conducted an ML Competition which you can find here: https://competition.bitgrit.net/competition/3

Below are the Problem description and guidelines.
#### Description

In the foreign exchange market, the smallest changes in international affairs and economics can have a huge effect on the conditions of a financial transaction, sometimes resulting in gigantic losses without the involved parties even being aware of it.

This possibility of financial losses resulting from the variation of exchange rates between local and foreign currency is called "exchange rate risk." Because the values of foreign currencies relative to a local currency are so unstable, their exchange rates are extremely difficult even for investors and exchange markets to accurately predict.

To find a solution to this issue, SoftBank has commissioned this competition as part of their research and development efforts. The successful submissions will be utilized in an exchange position transaction and management algorithm.

#### Guidelines

Predict the end-of-month exchange rate with given variables: market and economic news data.

The data set contains: training set, test set, and text features folders.

train & test
* id: encrypted date
* span: days to target date (end of month)
* target: exchange rate on target date / current exchange rate
* feature_00~feature_59_type5: various market data


Outputs should follow the format:

* id, target
* z, 0.9976 
* y, 1.0245 
* x, 1.07 

etc.

* Please note that the file should be sorted by id in descending order.

The Accuracy Score is Calculated on Root Mean Squared Error

##### Prizes are
  1st Prize - $6,000
  2nd Prize - $3,000
  3rd Prize - $1,000
  
  
More than **2200** people have participated and I ended up in **9th** Place, very happy to be in top 10.

