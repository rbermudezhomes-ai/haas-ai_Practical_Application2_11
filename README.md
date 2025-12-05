# What drives the price of a car?
Berkeley Haas Practical Application Project 2 [December 4, 2025]

### Goal:
- This project aims to analyze and identify the specifications, features, and options that determine a car's price. The analysis will use a curated dataset of 426K used cars sourced from a 3 million-record Kaggle collection. This reduced size facilitates quicker data processing. The result of the analysis will provide clear recommendation to our client -- used car dealership -- as to what customers value most when buying a used car.



### Jupyter Notebook:
- [Practical_Application_2.ipynb](https://github.com/rbermudezhomes-ai/haas-ai_Practical_Application2_11/blob/main/Practical_Application_2.ipynb)


### Dataset:
- Under folder /data: [vehicle.csv](https://github.com/rbermudezhomes-ai/haas-ai_Practical_Application2_11/blob/main/data/vehicles.csv)
- Source: UC Irvine Machine Learning Repository - [In Vehicle Coupon Recommendation](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation)

### Summary of Findings:
**The most valuable car features for customers include:**
- odometer is the top factor. Translating to low mileage is higher price. High mileage is less expensive.
- year(age) is second in the rank.
- odometer and year(age) - suggesting very low mileage and 3-5 years old new
- condition
- cylinders
- FWD
- pickup
- sedan


**By visually examining how the cars are distributed in the dataset, we can gain insight into their dominant features or factors.**
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
