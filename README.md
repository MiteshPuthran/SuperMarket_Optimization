# Super Market Optimization

This code is to find the associations between the different items from supermarket. The data set file consists of 25000 transactions with each transaction consisting of IDs of the items purchased together. The goal is to find the association between the items and try to find all sets of 3 items which were most frequently brought together.

## Approach:

### 1. Load the dataset

Read the data set which is in the string format and convert them into list.

### 2. Processing and the Algorithm

* Firstly we generate candidate sets which includes each items with their frequency of occurance in all the transactions. 
* The next step involves getting the frequency counts for every pair of items when combined together
* After obtaining the frequent item sets, we find the association rules for them.
* Using Aprori Algorithm we find the support for the items sets and return the desired results.

### 3. Output

Write the results of the item sets accociation into a file 
