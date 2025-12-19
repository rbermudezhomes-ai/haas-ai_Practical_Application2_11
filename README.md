# What drives the price of a car?
Berkeley Haas Practical Application Project 2 [December 4, 2025]

### Goal:
This project aims to analyze and identify the specifications, features, and options that determine a car's price. The analysis will use a curated dataset of 426K used cars sourced from a 3 million-record Kaggle collection. This reduced size facilitates quicker data processing. The result of the analysis will provide clear recommendation to our client -- used car dealership -- as to what car features drive the price of the car.



### Jupyter Notebook:
- [Practical_Application_2.ipynb](https://github.com/rbermudezhomes-ai/haas-ai_Practical_Application2_11/blob/main/Practical_Application_2.ipynb)


### Dataset:
- /data: [vehicle.csv](https://github.com/rbermudezhomes-ai/haas-ai_Practical_Application2_11/blob/main/data/vehicles.csv)
- Source: [Kaggle Dataset - US Used Cars](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset)


### Folders:
- data folder: contains the vehicle dataset(.csv)
- image folder: contains image of **CRISP-DM Framework** and a photo of a famous car salesman

  
### Summary of Findings:

We have developed and evaluated three regression models namely **Ordinary Least Squares (OLS) linear regression, Ridge regression, and Lasso regression** to improve car price estimation. Our models demonstrate significant improvement over baseline predictions, __reducing pricing errors by more than 35%__.


**Performance Improvement:**

Key Improvement - RMSE (Average Prediction Error):

- Baseline: 12,855
- Our Model: 8,269
- __Error Reduction: -$4,586 (35% reduction)__

All three regression models have significantly reduce the prediction error. The models reduced the root mean squared error(RMSE) by more than 35%.
This means our models can predict car prices with an average error of approximately $8,200-$8,300, compared to simply using the average price of $12,855.


**Example of Model Prediction:**

When predicting a $40,000 car:

- Baseline: Typically off by $13K (prediction price range is $27K-$53K)
- New Model: Typically off by $8K (prediction price range is $32K-$48K)

  
**Model Comparison:**

All three models performed nearly identical. The consistency indicates:

- Multiple approaches validate the same results
- Our models predict car prices with 36% better accuracy
- 91 features selected for maximum accuracy (as shown in the dataframe below)


**Top 10 Drivers of Vehicle Value**

Key factors identified by the Lasso model as having the greatest impact on price.

1. car age
2. odometer reading
3. by model
4. region
5. pick-up truck
6. convertible cars
7. odometer and car age (low mileage and slightly use car)
8. sedan
9. state of Iowa
10. state of Colorado

*__The final model evaluates 91 unique variables__ that influence car pricing. For a detailed list of all features and their relative impact, please refer to the detailed [Practical_Application_2.ipynb](https://github.com/rbermudezhomes-ai/haas-ai_Practical_Application2_11/blob/main/Practical_Application_2.ipynb).

**Vehicle Inventory Analysis - Key Feature Distributions**
- Size: Full-size and Medium-size vehicles are the most frequent sizes.
- Cylinder: 6-cylinder and 4-cylinder engines are the most frequent.
- Condition: Good and Excellent condition ratings are the most common by far.
- Drive: 4WD and FWD are the most frequent types.
- Color : The top 3 colors are white, black, and silver.
- Car Type : Sedan, SUV, Pickup are the most frequet type.
- Status : 80% - 90% have a clean title.
- Transmission : Automatic transmission is the most common by far.
- Fuel Type : Gasoline is the most frequent fuel type by far.
- Manufacturer : The top 3 manufacturers are Ford, Chevrolet, and Toyota.
- Model : The top 2 models are Ford F150 and Silverado 1500.
