# Prediction of Product Sales
## Analysis Procedure
This project, we want to predict the Item-Outlet-Sales for four different stores. The overall objective of this analysis data is to creat a model that can predict the food item sales.
We need to check the relationships between all feature in the datasets
**Author**: Mohammad Khilfeh

### Business problem:
The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.


### Data:
Dataset feature in this project contain of three types: Nominal , Ordinal , Numerical features. 


### Exploratory Data:
#### Relatioins ships in numeric feature using heat map.
![image](https://github.com/user-attachments/assets/3ee392d7-01bd-449c-ab86-f9b9723c5006)

The only numeric feature can influence the target is Item_MRV

---------------------------------------------------
#### Outlet_Size Vs Item_Outlet_Sales
![image](https://github.com/user-attachments/assets/57c7bf46-a8fa-4bbc-aa70-692f0d9ba646)

I can say the outlet size can influence the item outlet sales. 
The medium size of outlets achieves the high sales.

-----------------------------------------------

## Final Model 

1.  I tend to choose the RandomForest model after tuninig due to the slight difference between the training and testing data.
     However, this model still not well-fitted becouse of relatively low results in R^2 values and needs more improvment.


3.  Regarding the MAE values in the mentioned model above, testing data shows high results which indecates high value of error in item sales prices.
     Moreover, the 738$ implies a high variance  from the mean value in this data.
     Therefore, this range of error is considered not acceptable regarding our target.


## Recommendations:
I recommend to use other deep processes like Feature enginnering and Nueral Networks models.











