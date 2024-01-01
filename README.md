# Bread Basket Association Rule Mining with Apriori

## Goal

This project uses an association analysis to identify frequent item sets in transactions at a British bakery. Those itemsets will then be used to recommend an actionable business insight to the bakery.

## Data 

The [dataset](https://gist.githubusercontent.com/GregKuhlmann/1605ab44ac19c7edea5501d7a2dcc122/raw/1ad3ac582646a5389ea022e7d0e8e43686f3ffec/BreadBasket.csv) to be analyzed is from "The Bread Basket", a bakery located in Edinburgh.

## Data Analysis 

![image](https://github.com/catherinealeal/BreadBasketAssociationAnalysis/assets/100166102/b90164d4-095f-41bb-a5ec-550b8e7ca9a3)

There are 94 unique items and 9465 unique transactions.

## Creating Frequent Itemsets 

The dataset first needed to be converted to a transaction array using One Hot Encoding. The transformed dataframe could then be used to find frequent itemsets using the Apriori method with a minimum support of 20. 

## Generate Strong Rules 

Once the itemsets were generated, an association rule analysis was performed to identify items frequently purchased together. Four different metrics were used to yield rules with the most utility. 

## Conclusion: Actionable Business Insight 

The most clear result of this analysis is that coffee is by far the most bought item, no matter what else the transaction includes. Based on the fact that customers are very likely to buy coffee when buying anything else, I would suggest the bakery upcharges coffee in order to increase their sales income. I think that customers would continue purchasing the coffee, even if it is a bit more expensive. 

