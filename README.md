# Quality of LIfe Index 2020

PurchasingPowerPPIR_decisiontree.ipynb

This decision tree visualization deals with the classification of the purchasing power index of different cities around the world in terms of their property price to income ratio. 

Purchasing Power Index (PPI) and Property Price to Income Ratio (PPIR) used in the dataset used for this visualization is used as a metric to determine the Quality of Life Index (QLI) of this list of cities. According to Numbeo, the data compiler, PPI and QLI are directly proportional to one another whereas QLI and PPIR are inversely proportional to one another. The property price to income ratio data of all the cites has been broken down into four classes: very high, high, low and very low based on its range. The purchasing power index shows purchasing power in buying goods and services in the given city for the average net salary in that city relative to the purchasing power of New York City.

The resutls of this analysis gives the accuracy of 59 %. The variables, purchasing power index and property price to income ratio, presented a positive correlation of 0.7. This implies a directly proportional relationship between PPI and PPIR in the absence of QLI. Involvement of the QLI evaluation equation, where  PPI and QLI are directly proportional to one another whereas QLI and PPIR are inversely proportional to one another, maybe the reason for a lower accuracy in the decision tree classifier in constrast to a high correlation.  

About the economic meaning, this exercise intended to compare the relation between housing affordability and purchasing power to look for the possibility of comparing goods and services pricing between countries that have different currencies and economic conditions. There is a correlation between housing prices and a decrease in purchasing power like the relationship between inflation and any limited supply of goods (Nguyen 2020).  However, the impact of decreasing housing affordability is more severe as it signals a housing crisis and economic inequality as people who are most impacted by it are low-wage and blue-collar workers (Florida 2018).  Besides, this analysis could also lead to finding a better metric for the market analysis of a geographical location. So, the implications of this analysis could help with research on the financial and economic situation across national economies and hence could be useful for professionals of a financial market, investors, representatives of commercial companies, as well as for government bodies for planning and policy purposes.


QLIpredictionregression.ipynb

In this exercise, we compare decision tree regressor and mulitple regression for the prediction of Quality of Life Index (QLI) with the help of variables presented in the dataset. We also used Principal Component Analysis (PCA) for dimesnion reduction to combat the instances of overfitting due to a high dimensions of dataset. 

Mulitple regression on four principle components allowed a test accuracy of around 93% whereas Decision Tree regressor on the four principle componenets presented a test accuracy of around 85%. In this scenario, the increased accuracy with the use of multiple regression cannot be attibuted to the large number of feature in comparison the the datset as we have used PCA for reduction of the dimensions and both decision tree and multiple regression have the same number of reduced features. 


