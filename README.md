# Grocery-Association_Rule_Mining-

Problem Statement: This is the problem of Association Rule Mining. In this dataset of grocery products, it is required to find out which items are bought together frequently.


Steps involved into developing this model

1. Convert the data from dataframe to list and split the items.
2. Perform pre-processing using TransactionEncoder and tranform the given dataset into logical dataset.
4. For mining frequent itemsets, apply apriori and check the support for each item.
5. Find out the frequently bought items  and their corresponding confidence by association_rules.

Algorithms used for predictions:
1. TransactionEncoder
2. apriori 
3. association_rules
